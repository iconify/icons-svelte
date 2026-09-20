<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhjziobee.css';
import '../../css/q/q7z1euqgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qhjziobee"/><path class="q7z1euqgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:male" {...props}></Icon>
