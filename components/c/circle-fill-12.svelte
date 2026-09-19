<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7jhm504f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<circle class="b7jhm504f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-fill-12" {...props}></Icon>
