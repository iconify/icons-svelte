<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1930tbml.css';
import '../../css/w/wqxo31blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1930tbml"/><path class="wqxo31blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mode-text-filled" {...props}></Icon>
