<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wex3ut39i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wex3ut39i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:radio" {...props}></Icon>
