<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypoo3bclo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ypoo3bclo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:abbr-ml" {...props}></Icon>
