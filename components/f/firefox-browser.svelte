<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh_1t7rje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh_1t7rje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:firefox-browser" {...props}></Icon>
