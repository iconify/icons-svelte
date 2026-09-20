<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvn7b8phk.css';
import '../../css/h/h07qv5bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvn7b8phk"/><path class="h07qv5bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:multiple-neutral-2-bold" {...props}></Icon>
