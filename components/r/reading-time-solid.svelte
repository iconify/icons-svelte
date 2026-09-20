<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uljtn5aar.css';
import '../../css/a/akh0cg09d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uljtn5aar"/><path clip-rule="evenodd" class="akh0cg09d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:reading-time-solid" {...props}></Icon>
