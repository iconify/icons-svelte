<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odxs4xb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="odxs4xb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fans" {...props}></Icon>
