<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbg421biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbg421biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:paperclip-attechment-horizontal" {...props}></Icon>
