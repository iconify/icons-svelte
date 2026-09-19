<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo0s_cctr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo0s_cctr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:refresh-02" {...props}></Icon>
