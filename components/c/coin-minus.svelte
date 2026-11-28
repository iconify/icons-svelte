<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvfk_ofog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvfk_ofog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:coin-minus" {...props}></Icon>
