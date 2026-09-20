<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yexlg6mkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yexlg6mkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:istio" {...props}></Icon>
