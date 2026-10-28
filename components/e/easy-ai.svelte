<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qttyvtdda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qttyvtdda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:easy-ai" {...props}></Icon>
