<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dacebrbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dacebrbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:clock-two" {...props}></Icon>
