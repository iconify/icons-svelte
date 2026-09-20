<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw08v2bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw08v2bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dashboard-check" {...props}></Icon>
