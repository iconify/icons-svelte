<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffu9thy4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":488};
const content = `<path class="ffu9thy4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:brightkite" {...props}></Icon>
