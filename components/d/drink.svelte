<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vry51s4gb.css';
import '../../css/w/wxx5nhb-e.css';
import '../../css/a/amd21sbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="vry51s4gb"/><circle class="wxx5nhb-e"/><path class="amd21sbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:drink" {...props}></Icon>
