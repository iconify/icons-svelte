<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm-2r_bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hm-2r_bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-right-up" {...props}></Icon>
