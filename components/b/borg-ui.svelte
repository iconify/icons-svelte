<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb4fn93xo.css';
import '../../css/u/u82ou6akr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="wb4fn93xo"/><path class="u82ou6akr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:borg-ui" {...props}></Icon>
