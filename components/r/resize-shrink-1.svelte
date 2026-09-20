<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beb8anbww.css';
import '../../css/j/jd-oqlcip.css';
import '../../css/g/g9-1kgbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beb8anbww"/><path class="jd-oqlcip"/><path class="g9-1kgbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:resize-shrink-1" {...props}></Icon>
