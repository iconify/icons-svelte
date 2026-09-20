<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voelf1xfy.css';
import '../../css/p/p7ctu3bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="voelf1xfy"/><path class="p7ctu3bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:power-off" {...props}></Icon>
