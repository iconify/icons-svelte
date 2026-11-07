<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb-qqv6dc.css';
import '../../css/j/j_2v-fbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hb-qqv6dc"/><path clip-rule="evenodd" class="j_2v-fbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:backspace-outline" {...props}></Icon>
