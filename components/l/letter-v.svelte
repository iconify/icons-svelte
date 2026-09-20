<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyb6_ersx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyb6_ersx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-v" {...props}></Icon>
