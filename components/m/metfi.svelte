<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpg0t8u7t.css';
import '../../css/c/ccmwlvz2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpg0t8u7t"/><path class="ccmwlvz2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:metfi" {...props}></Icon>
