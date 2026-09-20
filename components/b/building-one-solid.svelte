<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jswyppbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jswyppbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:building-one-solid" {...props}></Icon>
