<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1ze04blp.css';
import '../../css/d/doshyacby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1ze04blp"/><path class="doshyacby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:layers-alt-filled" {...props}></Icon>
