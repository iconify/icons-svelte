<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm1xjabun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm1xjabun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:hd" {...props}></Icon>
