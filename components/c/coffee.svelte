<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/n/nh6wfl.css';
import '../../css/y/ywbs5z.css';
import '../../css/r/rakmch.css';
import '../../css/s/so-to-0.css';
import '../../css/s/so-from-10.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c nh6wfl"/><path class="a0m25c ywbs5z"/><path class="a0m25c rakmch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:coffee" {...props}></Icon>
