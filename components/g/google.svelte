<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nab6klb5t.css';
import '../../css/b/bdbr-nauf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nab6klb5t"/><path class="bdbr-nauf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:google" {...props}></Icon>
