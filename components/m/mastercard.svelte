<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_e7l-b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="n_e7l-b5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mastercard" {...props}></Icon>
