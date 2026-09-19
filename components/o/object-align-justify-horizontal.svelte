<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgpyz6brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sgpyz6brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:object-align-justify-horizontal" {...props}></Icon>
