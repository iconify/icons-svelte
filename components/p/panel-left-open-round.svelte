<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj1ixbbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj1ixbbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-left-open-round" {...props}></Icon>
