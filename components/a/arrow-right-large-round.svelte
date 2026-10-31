<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn8k0jbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn8k0jbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-right-large-round" {...props}></Icon>
