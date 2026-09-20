<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjz-p9bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjz-p9bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:radar4" {...props}></Icon>
