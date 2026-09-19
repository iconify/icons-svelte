<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/h28-skbwv.css';
import '../../css/b/b7rjdgn0s.css';
import '../../css/l/ly00bcc9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="h28-skbwv"/><path class="b7rjdgn0s"/><path class="ly00bcc9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:node-remove" {...props}></Icon>
