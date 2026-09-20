<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgy5n6fkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgy5n6fkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:annoyed-ghost-solid" {...props}></Icon>
