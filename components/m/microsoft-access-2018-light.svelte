<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwc5rnbvb.css';
import '../../css/h/hp0eg7bwe.css';
import '../../css/i/i0fe7jb1f.css';
import '../../css/t/tlmciol3y.css';
import '../../css/p/plsr1krgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="jwc5rnbvb"/><path class="hp0eg7bwe"/><path class="i0fe7jb1f"/><path class="tlmciol3y"/><path class="plsr1krgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-access-2018-light" {...props}></Icon>
