<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmre1_bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmre1_bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-l" {...props}></Icon>
