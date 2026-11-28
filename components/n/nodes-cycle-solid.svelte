<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooogucbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ooogucbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:nodes-cycle-solid" {...props}></Icon>
