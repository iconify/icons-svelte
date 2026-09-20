<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knt09wfpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knt09wfpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:battery-empty" {...props}></Icon>
