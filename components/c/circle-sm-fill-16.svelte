<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebtg3dbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="ebtg3dbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-sm-fill-16" {...props}></Icon>
