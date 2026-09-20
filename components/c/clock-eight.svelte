<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4su09bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4su09bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:clock-eight" {...props}></Icon>
