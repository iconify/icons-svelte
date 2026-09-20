<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw_cjjfhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yw_cjjfhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:omega" {...props}></Icon>
