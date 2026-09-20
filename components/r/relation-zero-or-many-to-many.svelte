<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2abiolpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2abiolpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-zero-or-many-to-many" {...props}></Icon>
