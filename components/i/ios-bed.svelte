<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0po3xb8t.css';
import '../../css/b/bsha2ob5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x0po3xb8t"/><path class="bsha2ob5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-bed" {...props}></Icon>
