<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj1s1w6dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj1s1w6dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:compress" {...props}></Icon>
