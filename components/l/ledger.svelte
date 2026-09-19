<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rkw1i4bzy.css';
import '../../css/v/v3s6c5b_h.css';
import '../../css/a/al6bhxbby.css';
import '../../css/i/i9y6cgbxw.css';
import '../../css/j/j3s6udbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="rkw1i4bzy"/><path class="v3s6c5b_h"/><path class="al6bhxbby"/><path class="i9y6cgbxw"/><path class="j3s6udbbw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:ledger" {...props}></Icon>
