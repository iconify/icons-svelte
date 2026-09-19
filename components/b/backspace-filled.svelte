<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjv7a_47d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjv7a_47d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:backspace-filled" {...props}></Icon>
