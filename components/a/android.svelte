<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea-yh5bmv.css';
import '../../css/y/yscrwi0no.css';
import '../../css/f/fzgbg6_rc.css';
import '../../css/v/vqkge80ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ea-yh5bmv"/><path class="yscrwi0no"/><path class="fzgbg6_rc"/><path class="vqkge80ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:android" {...props}></Icon>
