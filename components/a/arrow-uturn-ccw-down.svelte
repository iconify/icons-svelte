<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7zdombkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d7zdombkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-uturn-ccw-down" {...props}></Icon>
