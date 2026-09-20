<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctiilac8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctiilac8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dice-6-solid" {...props}></Icon>
