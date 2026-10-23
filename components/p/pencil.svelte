<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrus7ebnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrus7ebnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pencil" {...props}></Icon>
