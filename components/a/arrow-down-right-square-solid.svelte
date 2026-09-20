<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi1xqabvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi1xqabvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-down-right-square-solid" {...props}></Icon>
