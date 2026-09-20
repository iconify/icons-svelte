<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq3-lvrxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq3-lvrxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:dice-four" {...props}></Icon>
