<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em3tw8a-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em3tw8a-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grip-vertical-duotone" {...props}></Icon>
