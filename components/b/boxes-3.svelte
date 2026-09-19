<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_ddvlnii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y_ddvlnii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:boxes-3" {...props}></Icon>
