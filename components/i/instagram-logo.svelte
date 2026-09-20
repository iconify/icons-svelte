<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpqnhmtil.css';
import '../../css/x/x42oxcctk.css';
import '../../css/h/hwh4m4bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wpqnhmtil"/><path clip-rule="evenodd" class="x42oxcctk"/><path clip-rule="evenodd" class="hwh4m4bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:instagram-logo" {...props}></Icon>
