<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp4tifbel.css';
import '../../css/b/bdbim4bgo.css';
import '../../css/t/tl0l83b8e.css';
import '../../css/d/d25mwn3tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kp4tifbel"/><path class="bdbim4bgo"/><path clip-rule="evenodd" class="tl0l83b8e"/><path clip-rule="evenodd" class="d25mwn3tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-signal-outline" {...props}></Icon>
