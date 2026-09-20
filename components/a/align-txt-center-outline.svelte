<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i817_ebjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i817_ebjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:align-txt-center-outline" {...props}></Icon>
