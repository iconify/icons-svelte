<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hehyoublm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hehyoublm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:float-left-outline" {...props}></Icon>
