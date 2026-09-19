<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srdcyza2r.css';
import '../../css/g/g7n3rd2ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srdcyza2r"/><path class="g7n3rd2ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:discord" {...props}></Icon>
