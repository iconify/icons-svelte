<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm8sp9grg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vm8sp9grg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:atuin-dark" {...props}></Icon>
