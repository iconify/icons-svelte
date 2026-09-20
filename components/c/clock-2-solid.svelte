<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u27cibcer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u27cibcer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:clock-2-solid" {...props}></Icon>
