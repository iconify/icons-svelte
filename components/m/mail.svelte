<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/hyjq3ibzx.css';
import '../../css/j/j3qz157fz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hyjq3ibzx"/><path class="j3qz157fz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:mail" {...props}></Icon>
