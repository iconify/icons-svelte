<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofnamqm9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofnamqm9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:heart" {...props}></Icon>
