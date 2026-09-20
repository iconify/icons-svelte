<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0mybknet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0mybknet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:checkbox-multiple-line" {...props}></Icon>
