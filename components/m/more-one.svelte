<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-a1t9yth.css';
import '../../css/m/mprl4mbnb.css';
import '../../css/c/chpyfs2is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="c-a1t9yth"/><circle class="mprl4mbnb"/><circle class="chpyfs2is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:more-one" {...props}></Icon>
