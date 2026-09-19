<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0h8p0bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m0h8p0bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:hourglass-end" {...props}></Icon>
