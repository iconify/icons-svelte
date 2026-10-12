<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc85bcglw.css';
import '../../css/s/slcvs4yrl.css';
import '../../css/g/gdfre-uew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wc85bcglw"/><path class="slcvs4yrl"/><path class="gdfre-uew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:files-filled" {...props}></Icon>
