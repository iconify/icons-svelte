<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im587nbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im587nbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:quora" {...props}></Icon>
