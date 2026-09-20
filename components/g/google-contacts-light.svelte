<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p64es6bla.css';
import '../../css/f/fx4qy8b3n.css';
import '../../css/w/we___fbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p64es6bla"/><path class="fx4qy8b3n"/><path class="we___fbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-contacts-light" {...props}></Icon>
