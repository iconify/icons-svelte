<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbidgtbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nbidgtbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hermes-agent-dark" {...props}></Icon>
