<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqfa2vbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqfa2vbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-t-waves-solid" {...props}></Icon>
