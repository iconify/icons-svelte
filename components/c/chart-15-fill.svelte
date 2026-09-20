<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt0zg7bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt0zg7bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chart-15-fill" {...props}></Icon>
