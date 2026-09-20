<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lggc85m2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lggc85m2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-select-area-circle-dash-select-area-object-work" {...props}></Icon>
