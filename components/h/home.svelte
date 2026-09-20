<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v29gozgod.css';
import '../../css/m/mv0hob2-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v29gozgod"/><path class="mv0hob2-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:home" {...props}></Icon>
