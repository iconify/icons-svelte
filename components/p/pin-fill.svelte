<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1e7nwb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w1e7nwb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:pin-fill" {...props}></Icon>
