<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz1n53-_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz1n53-_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:equal-not" {...props}></Icon>
