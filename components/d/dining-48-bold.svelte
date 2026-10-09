<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmbj85spj.css';
import '../../css/o/orpaa3b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wmbj85spj"/><path class="orpaa3b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dining-48-bold" {...props}></Icon>
