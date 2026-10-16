<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cycwnxbny.css';
import '../../css/q/qzjyatb0i.css';
import '../../css/m/m4uhq0bmb.css';
import '../../css/p/px7fr0tbo.css';
import '../../css/h/h66nu-x9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cycwnxbny"/><path class="qzjyatb0i"/><path class="m4uhq0bmb"/><path class="px7fr0tbo"/><path class="h66nu-x9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mc4-connector-20-bold" {...props}></Icon>
