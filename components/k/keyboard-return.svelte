<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9p2bebfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="b9p2bebfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:keyboard-return" {...props}></Icon>
