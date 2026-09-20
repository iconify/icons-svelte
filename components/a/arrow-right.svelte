<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4ei0rm9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4ei0rm9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arrow-right" {...props}></Icon>
