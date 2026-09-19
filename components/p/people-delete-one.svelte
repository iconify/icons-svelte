<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gko5i1byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gko5i1byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:people-delete-one" {...props}></Icon>
