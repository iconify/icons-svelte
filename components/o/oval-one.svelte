<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahrb5lbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="ahrb5lbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:oval-one" {...props}></Icon>
