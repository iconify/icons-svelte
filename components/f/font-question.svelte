<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa7ydfgil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa7ydfgil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:font-question" {...props}></Icon>
