<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okr4k8bwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okr4k8bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-k-diamond" {...props}></Icon>
