<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jarc6s6ki.css';
import '../../css/s/sh9y-3b-t.css';
import '../../css/a/anpv6btnk.css';
import '../../css/j/jxw8_1b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jarc6s6ki wm-k"/><path class="sh9y-3b-t wm-k"/><path class="anpv6btnk wm-a"/><path class="jxw8_1b8y wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:backpack" {...props}></Icon>
