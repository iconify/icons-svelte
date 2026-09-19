<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un81jbcqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="un81jbcqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:instagram" {...props}></Icon>
