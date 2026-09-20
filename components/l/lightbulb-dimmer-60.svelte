<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5zf5nqcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5zf5nqcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulb-dimmer-60" {...props}></Icon>
