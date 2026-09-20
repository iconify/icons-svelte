<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9m2ddbuh.css';
import '../../css/p/pfsh8mdfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9m2ddbuh"/><path class="pfsh8mdfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:alpha-wallet" {...props}></Icon>
