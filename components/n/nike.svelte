<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euksjz92v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="euksjz92v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nike" {...props}></Icon>
