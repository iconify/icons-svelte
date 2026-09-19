<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vax5f8bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":961,"height":960};
const content = `<path class="vax5f8bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dominosix" {...props}></Icon>
