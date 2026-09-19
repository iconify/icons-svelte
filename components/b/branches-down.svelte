<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8pzq2q8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a8pzq2q8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:branches-down" {...props}></Icon>
