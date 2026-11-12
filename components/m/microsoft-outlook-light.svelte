<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv5gx-44j.css';
import '../../css/s/sobo_lk1b.css';
import '../../css/h/h33hifd-b.css';
import '../../css/i/i69id4bah.css';
import '../../css/o/ooiwd4u1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lv5gx-44j"/><path class="sobo_lk1b"/><path class="h33hifd-b"/><path class="i69id4bah"/><path class="ooiwd4u1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-outlook-light" {...props}></Icon>
