<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8_7d2xqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8_7d2xqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:pregnancy-pregnant-bold" {...props}></Icon>
