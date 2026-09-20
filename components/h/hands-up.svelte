<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhjziobee.css';
import '../../css/v/vm1oqwb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qhjziobee"/><path class="vm1oqwb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:hands-up" {...props}></Icon>
