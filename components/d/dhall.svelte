<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi4m82f8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi4m82f8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:dhall" {...props}></Icon>
