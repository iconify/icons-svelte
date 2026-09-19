<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_lwrw-gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c_lwrw-gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:book" {...props}></Icon>
