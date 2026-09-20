<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1upd6b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j1upd6b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-tika-dark" {...props}></Icon>
