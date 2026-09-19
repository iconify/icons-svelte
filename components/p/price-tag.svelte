<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agh5kobes.css';
import '../../css/f/fe-l95ejb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agh5kobes"/><path class="fe-l95ejb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:price-tag" {...props}></Icon>
