<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_brxd2on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="k_brxd2on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:ladder" {...props}></Icon>
