<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osspv9bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osspv9bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-shield-2-fill" {...props}></Icon>
