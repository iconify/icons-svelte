<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y85bi0b7a.css';
import '../../css/q/q3818dbqt.css';
import '../../css/f/fbiyt7hbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y85bi0b7a"/><path class="q3818dbqt"/><path class="fbiyt7hbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drawing-compass-20" {...props}></Icon>
