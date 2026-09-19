<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5yqucbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="u5yqucbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:dependabot" {...props}></Icon>
