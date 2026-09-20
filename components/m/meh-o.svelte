<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd_9zuben.css';
import '../../css/i/ihffxab9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vd_9zuben"/><path class="ihffxab9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:meh-o" {...props}></Icon>
