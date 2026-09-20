<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqb0h2zhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kqb0h2zhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-riding-swing" {...props}></Icon>
