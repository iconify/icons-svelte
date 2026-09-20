<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/safdbqb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="safdbqb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:parking-line" {...props}></Icon>
