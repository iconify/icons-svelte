<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqg3ftxno.css';
import '../../css/v/v6ayyo12g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqg3ftxno"/><path class="v6ayyo12g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-headphone" {...props}></Icon>
