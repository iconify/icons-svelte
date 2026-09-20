<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4jbqtvpk.css';
import '../../css/g/glxcbqcdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4jbqtvpk"/><path class="glxcbqcdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:balance-solid" {...props}></Icon>
