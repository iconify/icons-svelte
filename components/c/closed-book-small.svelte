<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixkerdb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ixkerdb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:closed-book-small" {...props}></Icon>
