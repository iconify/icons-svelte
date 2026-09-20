<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj11z5e7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj11z5e7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:credit-card-plus" {...props}></Icon>
