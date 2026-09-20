<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oflhhkbur.css';
import '../../css/r/rql-eabty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oflhhkbur"/><path class="rql-eabty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:mute" {...props}></Icon>
