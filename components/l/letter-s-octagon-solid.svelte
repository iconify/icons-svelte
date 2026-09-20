<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6owe0blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6owe0blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-s-octagon-solid" {...props}></Icon>
