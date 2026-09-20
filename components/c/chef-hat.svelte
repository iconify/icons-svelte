<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgw8fbnzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgw8fbnzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chef-hat" {...props}></Icon>
