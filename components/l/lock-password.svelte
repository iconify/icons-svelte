<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6h6mpbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6h6mpbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lock-password" {...props}></Icon>
