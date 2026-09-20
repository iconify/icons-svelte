<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csnou1l8n.css';
import '../../css/z/z6oybf-di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="csnou1l8n"/><path class="z6oybf-di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:bug-o" {...props}></Icon>
