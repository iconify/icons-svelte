<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au450cbud.css';
import '../../css/b/bztrvmj6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<ellipse class="au450cbud"/><circle class="bztrvmj6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:decimal-fill-16" {...props}></Icon>
