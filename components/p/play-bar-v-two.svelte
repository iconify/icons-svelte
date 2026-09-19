<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t67x14b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t67x14b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:play-bar-v-two" {...props}></Icon>
