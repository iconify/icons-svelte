<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g83i4kb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="g83i4kb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:hexo" {...props}></Icon>
