<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh2693boa.css';
import '../../css/f/fi8uxkbev.css';
import '../../css/w/w2vxx8m4b.css';
import '../../css/h/hbqk-zhur.css';
import '../../css/p/pwu498b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="lh2693boa"/><path class="fi8uxkbev"/><path class="w2vxx8m4b"/><path class="hbqk-zhur"/><path class="pwu498b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:antigua-and-barbuda" {...props}></Icon>
