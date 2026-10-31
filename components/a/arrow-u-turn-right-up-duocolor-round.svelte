<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yff31rbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yff31rbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-u-turn-right-up-duocolor-round" {...props}></Icon>
