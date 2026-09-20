<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plk8nejnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plk8nejnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chart-down" {...props}></Icon>
