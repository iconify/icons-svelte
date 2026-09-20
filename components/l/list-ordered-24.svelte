<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjrfh32jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjrfh32jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:list-ordered-24" {...props}></Icon>
