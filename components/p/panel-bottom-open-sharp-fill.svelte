<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw50-2a5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw50-2a5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-bottom-open-sharp-fill" {...props}></Icon>
