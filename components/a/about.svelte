<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbv6r8omk.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/l/lzbjlqyni.css';
import '../../css/a/asp4yobns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wbv6r8omk"/><g class="n1mjunbsu"><path class="lzbjlqyni"/><circle class="asp4yobns"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:about" {...props}></Icon>
