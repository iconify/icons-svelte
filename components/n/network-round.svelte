<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o95d7jbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o95d7jbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:network-round" {...props}></Icon>
