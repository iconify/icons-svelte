<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgo4n8spf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dgo4n8spf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:creditcard" {...props}></Icon>
