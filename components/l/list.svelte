<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnosue_qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnosue_qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:list" {...props}></Icon>
