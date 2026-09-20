<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v99l2mbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v99l2mbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:pathfinder-minus-front-2-solid" {...props}></Icon>
