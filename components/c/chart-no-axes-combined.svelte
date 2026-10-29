<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-5-68xlv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-5-68xlv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chart-no-axes-combined" {...props}></Icon>
