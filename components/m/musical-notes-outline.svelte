<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_5qwt2go.css';
import '../../css/b/b8j_7x21u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b_5qwt2go"/><path class="b8j_7x21u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:musical-notes-outline" {...props}></Icon>
