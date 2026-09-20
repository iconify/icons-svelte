<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn_0otsqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn_0otsqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lbr" {...props}></Icon>
