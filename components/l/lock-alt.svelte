<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piif4cchw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="piif4cchw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:lock-alt" {...props}></Icon>
