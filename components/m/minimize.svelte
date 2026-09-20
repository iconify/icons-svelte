<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o38zo9b0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o38zo9b0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:minimize" {...props}></Icon>
