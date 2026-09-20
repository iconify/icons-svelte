<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql3a4ib0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql3a4ib0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-s-square-solid" {...props}></Icon>
