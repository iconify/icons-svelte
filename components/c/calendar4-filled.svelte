<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te1zobbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te1zobbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calendar4-filled" {...props}></Icon>
