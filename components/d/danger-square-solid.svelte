<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d04alkbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d04alkbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:danger-square-solid" {...props}></Icon>
