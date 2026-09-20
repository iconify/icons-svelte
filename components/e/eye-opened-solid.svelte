<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6uz3dquh.css';
import '../../css/c/cn5tumcdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6uz3dquh"/><path class="cn5tumcdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:eye-opened-solid" {...props}></Icon>
