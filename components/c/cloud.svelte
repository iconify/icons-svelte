<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coxqc0blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="coxqc0blz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cloud" {...props}></Icon>
