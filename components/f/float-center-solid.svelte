<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqq0ivbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hqq0ivbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:float-center-solid" {...props}></Icon>
