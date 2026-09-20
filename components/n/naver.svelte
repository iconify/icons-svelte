<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6n9f9bcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6n9f9bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:naver" {...props}></Icon>
