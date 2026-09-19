<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcw5r9b9i.css';
import '../../css/j/jtvessbvn.css';
import '../../css/o/oxb2pjboe.css';
import '../../css/b/bo1s8jdel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gcw5r9b9i"/><path class="jtvessbvn"/><path class="oxb2pjboe"/><path class="bo1s8jdel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:questions" {...props}></Icon>
