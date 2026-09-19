<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl8h52i2e.css';
import '../../css/w/wadzaq9on.css';
import '../../css/v/v5qe0mb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kl8h52i2e"/><path class="wadzaq9on"/><path class="v5qe0mb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:csharp" {...props}></Icon>
