<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpibj_16d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpibj_16d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:export3" {...props}></Icon>
