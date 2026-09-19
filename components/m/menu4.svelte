<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-x8h-psw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":16};
const content = `<path class="f-x8h-psw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:menu4" {...props}></Icon>
