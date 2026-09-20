<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mndd9jbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mndd9jbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:play-expressive" {...props}></Icon>
