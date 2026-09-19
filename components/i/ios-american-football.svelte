<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0avm8bpo.css';
import '../../css/f/fm0ubtb9b.css';
import '../../css/t/tvfrm8b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x0avm8bpo"/><path class="fm0ubtb9b"/><path class="tvfrm8b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-american-football" {...props}></Icon>
