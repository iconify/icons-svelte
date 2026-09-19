<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uis23wbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="uis23wbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:baidu" {...props}></Icon>
