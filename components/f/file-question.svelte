<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncwsyc6me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncwsyc6me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-question" {...props}></Icon>
