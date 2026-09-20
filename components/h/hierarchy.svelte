<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjzc62use.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bjzc62use"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:hierarchy" {...props}></Icon>
