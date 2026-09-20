<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1a1axb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1a1axb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-long-up" {...props}></Icon>
