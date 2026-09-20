<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdq72bcjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdq72bcjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:fork-solid" {...props}></Icon>
