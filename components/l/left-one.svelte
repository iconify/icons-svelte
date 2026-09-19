<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m63m8hbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m63m8hbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:left-one" {...props}></Icon>
