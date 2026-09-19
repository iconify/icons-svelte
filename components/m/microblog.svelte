<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjt944sev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="qjt944sev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:microblog" {...props}></Icon>
