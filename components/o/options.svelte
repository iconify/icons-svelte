<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nme7svmcs.css';
import '../../css/f/fnrrisblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nme7svmcs"/><path class="fnrrisblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:options" {...props}></Icon>
