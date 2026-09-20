<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-61lmm4b.css';
import '../../css/v/v-wrjcb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-61lmm4b"/><path class="v-wrjcb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:font-size-bold" {...props}></Icon>
