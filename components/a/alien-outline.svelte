<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riiwu8b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="riiwu8b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:alien-outline" {...props}></Icon>
