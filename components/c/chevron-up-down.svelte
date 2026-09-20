<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khjrhnv3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khjrhnv3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-up-down" {...props}></Icon>
