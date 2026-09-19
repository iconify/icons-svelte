<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npypd61ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="npypd61ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:billed-cap" {...props}></Icon>
