<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/ky7fzbcuf.css';
import '../../css/j/jvtjbnueh.css';
import '../../css/g/gz0j8xbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ky7fzbcuf"/><path class="jvtjbnueh"/><path class="gz0j8xbyn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:play-list" {...props}></Icon>
