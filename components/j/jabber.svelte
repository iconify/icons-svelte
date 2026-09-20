<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i153x3bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i153x3bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:jabber" {...props}></Icon>
