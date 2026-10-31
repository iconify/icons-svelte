<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv73hovyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv73hovyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-top-fill-round" {...props}></Icon>
