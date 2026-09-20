<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqof30ala.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rqof30ala"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:align-left-outline" {...props}></Icon>
