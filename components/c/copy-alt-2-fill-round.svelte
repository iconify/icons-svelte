<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eko1wh1jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eko1wh1jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:copy-alt-2-fill-round" {...props}></Icon>
