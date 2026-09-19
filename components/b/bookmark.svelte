<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6j73nbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="o6j73nbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:bookmark" {...props}></Icon>
