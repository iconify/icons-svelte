<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjp3m3bor.css';
import '../../css/t/tn3ef2i2f.css';
import '../../css/b/b2fgv7b-a.css';
import '../../css/w/we48irbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gjp3m3bor"/><path class="tn3ef2i2f"/><path class="b2fgv7b-a"/><path class="we48irbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:billiards" {...props}></Icon>
