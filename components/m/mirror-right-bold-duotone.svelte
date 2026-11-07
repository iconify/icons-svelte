<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa5889vlx.css';
import '../../css/a/aa2olkmfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa5889vlx"/><path clip-rule="evenodd" class="aa2olkmfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mirror-right-bold-duotone" {...props}></Icon>
