<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qox0n4a5t.css';
import '../../css/e/e05xc9bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qox0n4a5t"/><path clip-rule="evenodd" class="e05xc9bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:android-24" {...props}></Icon>
