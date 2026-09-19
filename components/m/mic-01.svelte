<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8awi8bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8awi8bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mic-01" {...props}></Icon>
