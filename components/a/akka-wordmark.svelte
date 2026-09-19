<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb_6iza3u.css';
import '../../css/g/gi3nmwdkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gb_6iza3u"/><path class="gi3nmwdkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:akka-wordmark" {...props}></Icon>
