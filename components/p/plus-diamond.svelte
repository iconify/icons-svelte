<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs23_ib0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hs23_ib0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:plus-diamond" {...props}></Icon>
