<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewl61acth.css';
import '../../css/r/r58_0ub5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewl61acth"/><path class="r58_0ub5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:package-upgrade-outlined" {...props}></Icon>
