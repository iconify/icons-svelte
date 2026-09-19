<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxlj-rh_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxlj-rh_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:apps-filled" {...props}></Icon>
