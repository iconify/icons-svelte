<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7s5l2bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7s5l2bgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:label-solid" {...props}></Icon>
