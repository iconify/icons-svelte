<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t07md_6bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t07md_6bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dots-octagon" {...props}></Icon>
