<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6przlbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6przlbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-k-circle" {...props}></Icon>
