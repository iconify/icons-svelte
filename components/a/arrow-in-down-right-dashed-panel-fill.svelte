<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o07u8dbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o07u8dbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-in-down-right-dashed-panel-fill" {...props}></Icon>
