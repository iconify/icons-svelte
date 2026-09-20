<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpg2ybbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpg2ybbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:paint" {...props}></Icon>
