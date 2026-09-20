<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/r/rfiktw.css';
import '../../css/y/yi3myz.css';
import '../../css/g/gjd-ug.css';
import '../../css/s/so-from-10.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c rfiktw"/><path class="a0m25c yi3myz"/><path class="a0m25c gjd-ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chevron-small-triple-down" {...props}></Icon>
