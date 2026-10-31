<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3dt8sb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3dt8sb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:martini-fill-round" {...props}></Icon>
