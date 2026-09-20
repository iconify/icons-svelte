<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/ziygmcxzn.css';
import '../../css/l/l2xaw8bcb.css';
import '../../css/y/yla1pjbjb.css';
import '../../css/r/runq6zfif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ziygmcxzn"/><path class="l2xaw8bcb"/><path class="yla1pjbjb"/><path class="runq6zfif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:modern-music-dj" {...props}></Icon>
