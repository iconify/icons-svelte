<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edoc9w87l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":488};
const content = `<path class="edoc9w87l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:pingchat" {...props}></Icon>
