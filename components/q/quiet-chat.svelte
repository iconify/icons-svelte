<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r60ej9bjx.css';
import '../../css/f/f91k7jbaj.css';
import '../../css/x/xs2wbd9sc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r60ej9bjx"/><path class="f91k7jbaj"/><path class="xs2wbd9sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quiet-chat" {...props}></Icon>
