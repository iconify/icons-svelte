<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okm62lwzp.css';
import '../../css/j/jlel-zbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="okm62lwzp"/><path class="jlel-zbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:at-sign-20-bold" {...props}></Icon>
