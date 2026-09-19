<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol8f0qb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ol8f0qb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:doc-circle-fill" {...props}></Icon>
