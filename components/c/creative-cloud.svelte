<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3k9y0miw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m3k9y0miw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:creative-cloud" {...props}></Icon>
