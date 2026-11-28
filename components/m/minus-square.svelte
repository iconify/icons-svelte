<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxk-8juiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxk-8juiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:minus-square" {...props}></Icon>
