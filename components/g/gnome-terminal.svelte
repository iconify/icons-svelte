<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbplu9bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbplu9bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gnome-terminal" {...props}></Icon>
