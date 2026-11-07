<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdob9slbu.css';
import '../../css/w/womkpu5er.css';
import '../../css/d/dhs0g5bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdob9slbu"/><path class="womkpu5er"/><path class="dhs0g5bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:quit-pip-bold-duotone" {...props}></Icon>
