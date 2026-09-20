<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7gl5qb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="r7gl5qb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:circle" {...props}></Icon>
