<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neqmi2sea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="neqmi2sea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:pen" {...props}></Icon>
