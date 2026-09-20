<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j51w7z-wj.css';
import '../../css/q/qg43yj1um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j51w7z-wj"/><path class="qg43yj1um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:location-arrow-circle-o" {...props}></Icon>
