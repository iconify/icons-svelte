<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te2afuoap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="te2afuoap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:keyframe-minus-in-solid" {...props}></Icon>
