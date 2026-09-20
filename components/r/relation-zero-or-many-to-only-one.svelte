<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9kxaq83j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9kxaq83j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-zero-or-many-to-only-one" {...props}></Icon>
