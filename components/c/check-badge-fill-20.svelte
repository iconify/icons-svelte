<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5fuxbhra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x5fuxbhra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-badge-fill-20" {...props}></Icon>
