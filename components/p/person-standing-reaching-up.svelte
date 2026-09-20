<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9cfj-b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n9cfj-b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-standing-reaching-up" {...props}></Icon>
