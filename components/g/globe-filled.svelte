<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ned20jbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ned20jbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:globe-filled" {...props}></Icon>
