<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnhsm5wjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnhsm5wjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:kivy" {...props}></Icon>
