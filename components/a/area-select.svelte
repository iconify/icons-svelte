<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itbt_h6ys.css';
import '../../css/o/o5ayvslgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="itbt_h6ys"/><path class="o5ayvslgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:area-select" {...props}></Icon>
