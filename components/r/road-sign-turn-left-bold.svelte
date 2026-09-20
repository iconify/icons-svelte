<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx6no8bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx6no8bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:road-sign-turn-left-bold" {...props}></Icon>
