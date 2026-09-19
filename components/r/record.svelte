<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/s/s9tz2zumz.css';
import '../../css/i/i1b443bkt.css';
import '../../css/g/gilfwhj-b.css';
import '../../css/y/yjv45b33a.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGsbUJ6bai"><g class="v3_i3wktz"><rect class="s9tz2zumz"/><path class="i1b443bkt"/><path class="gilfwhj-b"/><path class="yjv45b33a"/></g></mask></defs><path mask="url(#SVGsbUJ6bai)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:record" {...props}></Icon>
