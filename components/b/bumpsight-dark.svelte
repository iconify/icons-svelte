<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxmz3ienn.css';
import '../../css/w/wm9w19bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="xxmz3ienn"/><path class="wm9w19bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bumpsight-dark" {...props}></Icon>
