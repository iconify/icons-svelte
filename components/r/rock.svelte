<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs3j8ab6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs3j8ab6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:rock" {...props}></Icon>
