<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hufe2dbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hufe2dbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pnb" {...props}></Icon>
