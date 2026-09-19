<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h09gf8bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h09gf8bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:code-compare" {...props}></Icon>
