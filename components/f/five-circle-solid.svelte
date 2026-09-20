<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htqchfz1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htqchfz1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:five-circle-solid" {...props}></Icon>
