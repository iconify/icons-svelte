<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks918j6of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks918j6of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:nano-staged-light" {...props}></Icon>
