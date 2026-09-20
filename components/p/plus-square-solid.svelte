<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpzczrkzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpzczrkzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:plus-square-solid" {...props}></Icon>
