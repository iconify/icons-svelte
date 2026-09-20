<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnl21hbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnl21hbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-down-left-solid" {...props}></Icon>
