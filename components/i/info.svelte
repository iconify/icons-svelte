<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t48yxwfsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t48yxwfsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:info" {...props}></Icon>
