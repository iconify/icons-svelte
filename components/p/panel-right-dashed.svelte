<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-n617zmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-n617zmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:panel-right-dashed" {...props}></Icon>
