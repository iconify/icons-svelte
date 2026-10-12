<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx32cnbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tx32cnbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:medical-cross-20" {...props}></Icon>
