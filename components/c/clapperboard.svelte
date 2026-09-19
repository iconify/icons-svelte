<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp6fzabyy.css';
import '../../css/n/nph7vibnr.css';
import '../../css/x/xnq8w68sz.css';
import '../../css/g/grxh9gs-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jp6fzabyy"/><path class="nph7vibnr"/><circle class="xnq8w68sz"/><path class="grxh9gs-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:clapperboard" {...props}></Icon>
