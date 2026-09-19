<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfrh88v8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dfrh88v8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:chevron-down-wide" {...props}></Icon>
