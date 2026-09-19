<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvwb1mbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvwb1mbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:egg" {...props}></Icon>
