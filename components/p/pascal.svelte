<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf2yv3b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf2yv3b4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:pascal" {...props}></Icon>
