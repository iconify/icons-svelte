<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8fv5cbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8fv5cbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:play-bar-v-alt" {...props}></Icon>
