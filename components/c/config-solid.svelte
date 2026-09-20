<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqm66bb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqm66bb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:config-solid" {...props}></Icon>
