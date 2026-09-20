<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slxt4ccor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slxt4ccor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:awesome-lists" {...props}></Icon>
