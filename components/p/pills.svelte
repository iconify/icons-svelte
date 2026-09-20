<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltf0sebud.css';
import '../../css/a/ahpr7q3lo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ltf0sebud"/><path class="ahpr7q3lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:pills" {...props}></Icon>
