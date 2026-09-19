<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfdbrwbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qfdbrwbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:microsoft" {...props}></Icon>
