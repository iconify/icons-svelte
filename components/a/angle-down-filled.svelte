<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze9lbvbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ze9lbvbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:angle-down-filled" {...props}></Icon>
