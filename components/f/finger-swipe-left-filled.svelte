<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcf2g90wf.css';
import '../../css/g/gfumbbcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcf2g90wf"/><path class="gfumbbcog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:finger-swipe-left-filled" {...props}></Icon>
