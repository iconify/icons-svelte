<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpfy7f3fe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpfy7f3fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:flathub" {...props}></Icon>
