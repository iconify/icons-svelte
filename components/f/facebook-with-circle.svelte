<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_6afjkun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e_6afjkun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:facebook-with-circle" {...props}></Icon>
