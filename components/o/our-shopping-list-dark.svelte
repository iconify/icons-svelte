<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri15mwhnp.css';
import '../../css/q/qjx3e9jap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ri15mwhnp"/><path class="qjx3e9jap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:our-shopping-list-dark" {...props}></Icon>
