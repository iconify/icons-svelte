<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8dzo7vbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8dzo7vbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:letters-r" {...props}></Icon>
