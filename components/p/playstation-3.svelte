<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on0yoobms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on0yoobms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:playstation-3" {...props}></Icon>
