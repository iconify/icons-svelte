<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbxme9fqn.css';
import '../../css/w/wi8y19aeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qbxme9fqn"/><path class="wi8y19aeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:expand-square" {...props}></Icon>
