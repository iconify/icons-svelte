<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nozaz7b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nozaz7b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ai2" {...props}></Icon>
