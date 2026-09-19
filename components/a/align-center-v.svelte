<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo5uhngrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo5uhngrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:align-center-v" {...props}></Icon>
