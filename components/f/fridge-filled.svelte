<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phe-lywxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phe-lywxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fridge-filled" {...props}></Icon>
