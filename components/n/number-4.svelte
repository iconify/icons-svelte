<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gguu4r_oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gguu4r_oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-4" {...props}></Icon>
