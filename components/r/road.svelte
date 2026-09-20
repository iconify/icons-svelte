<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft81xcc4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ft81xcc4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:road" {...props}></Icon>
