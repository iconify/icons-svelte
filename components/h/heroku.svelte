<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaec7bbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="eaec7bbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:heroku" {...props}></Icon>
