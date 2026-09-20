<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edlu_rqaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edlu_rqaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-infor-fill" {...props}></Icon>
