<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iddj-1bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="iddj-1bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:day-rain" {...props}></Icon>
