<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6_1xzbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b6_1xzbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:codefactor-logo-block" {...props}></Icon>
