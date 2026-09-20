<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk3wpst3e.css';
import '../../css/y/yp_-cobqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk3wpst3e"/><path class="yp_-cobqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:night-moon-begin-bold" {...props}></Icon>
