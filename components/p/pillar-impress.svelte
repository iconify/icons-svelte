<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg_meg-on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg_meg-on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pillar-impress" {...props}></Icon>
