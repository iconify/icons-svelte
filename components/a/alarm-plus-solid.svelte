<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh0succoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh0succoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:alarm-plus-solid" {...props}></Icon>
