<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd8nq5kls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd8nq5kls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:axios" {...props}></Icon>
