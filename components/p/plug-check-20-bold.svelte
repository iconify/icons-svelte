<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez54jb8ys.css';
import '../../css/w/w5rh0bcun.css';
import '../../css/p/pw_enhbqu.css';
import '../../css/x/xngn3sb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ez54jb8ys"/><path class="w5rh0bcun"/><path class="pw_enhbqu"/><path class="xngn3sb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plug-check-20-bold" {...props}></Icon>
