<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de42klgpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de42klgpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:inbox-2-line" {...props}></Icon>
