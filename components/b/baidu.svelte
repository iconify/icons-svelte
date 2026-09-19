<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcznqro8c.css';
import '../../css/g/gsn7st_me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcznqro8c"/><path class="gsn7st_me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:baidu" {...props}></Icon>
