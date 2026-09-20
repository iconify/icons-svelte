<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xikpskncw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xikpskncw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:login6-filled" {...props}></Icon>
