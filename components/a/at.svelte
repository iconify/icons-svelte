<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jap95xb6l.css';
import '../../css/g/gkzp8sbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jap95xb6l"/><path class="gkzp8sbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:at" {...props}></Icon>
