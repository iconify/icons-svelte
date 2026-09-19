<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/hgo0pgs3a.css';
import '../../css/p/p-hc53bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hgo0pgs3a"/><path class="p-hc53bai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-double-up" {...props}></Icon>
