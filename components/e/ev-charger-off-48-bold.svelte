<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxbfs7m-k.css';
import '../../css/m/m2anmnf8b.css';
import '../../css/d/d27j7obsk.css';
import '../../css/p/p34gu6lai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hxbfs7m-k"/><path class="m2anmnf8b"/><path class="d27j7obsk"/><path class="p34gu6lai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-charger-off-48-bold" {...props}></Icon>
