<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tap2fcboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tap2fcboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:align-right-outline" {...props}></Icon>
