<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asy5lslmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asy5lslmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mobile3-filled" {...props}></Icon>
