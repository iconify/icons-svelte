<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-51n6uqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-51n6uqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:align-left" {...props}></Icon>
