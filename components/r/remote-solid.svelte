<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znj3rrbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znj3rrbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:remote-solid" {...props}></Icon>
