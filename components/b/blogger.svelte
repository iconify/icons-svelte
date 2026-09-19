<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azm_1muof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="azm_1muof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:blogger" {...props}></Icon>
