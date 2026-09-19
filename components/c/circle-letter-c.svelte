<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfdnp7j9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yfdnp7j9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-letter-c" {...props}></Icon>
