<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb775zgkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gb775zgkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:bars-ascending-align-left-arrow-down" {...props}></Icon>
