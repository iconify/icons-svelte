<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x59ytrbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x59ytrbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:list-strong" {...props}></Icon>
