<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdnzs0byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdnzs0byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-f-circle-solid" {...props}></Icon>
