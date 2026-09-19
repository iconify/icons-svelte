<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-3ebjqeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":494,"height":512};
const content = `<path class="l-3ebjqeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:cdf" {...props}></Icon>
