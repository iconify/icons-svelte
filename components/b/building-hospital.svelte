<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxoh7_kwo.css';
import '../../css/j/jjd6ecb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxoh7_kwo"/><path class="jjd6ecb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:building-hospital" {...props}></Icon>
