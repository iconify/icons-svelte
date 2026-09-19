<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg46exbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg46exbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-long-up" {...props}></Icon>
