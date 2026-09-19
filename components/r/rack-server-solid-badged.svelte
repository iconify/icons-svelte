<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9canfbpr.css';
import '../../css/g/gxw0w0bbb.css';
import '../../css/f/f18t8w0qw.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--badged clr-i-solid-path-1--badged g9canfbpr"/><path class="clr-i-solid--badged clr-i-solid-path-2--badged gxw0w0bbb"/><path class="clr-i-solid--badged clr-i-solid-path-3--badged f18t8w0qw"/><circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-4--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:rack-server-solid-badged" {...props}></Icon>
