<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtgmy3b7z.css';
import '../../css/u/uskkbacik.css';
import '../../css/n/nfmjk5b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qtgmy3b7z"/><path class="uskkbacik"/><path class="nfmjk5b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ammeter-48-bold" {...props}></Icon>
