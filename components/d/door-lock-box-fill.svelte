<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5k2us3qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5k2us3qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:door-lock-box-fill" {...props}></Icon>
