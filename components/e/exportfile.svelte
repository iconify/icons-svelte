<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqh-rfpqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pqh-rfpqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:exportfile" {...props}></Icon>
