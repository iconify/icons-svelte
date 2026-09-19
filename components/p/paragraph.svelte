<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi522ibcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi522ibcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:paragraph" {...props}></Icon>
