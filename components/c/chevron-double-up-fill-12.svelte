<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8dohpt2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="x8dohpt2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-double-up-fill-12" {...props}></Icon>
