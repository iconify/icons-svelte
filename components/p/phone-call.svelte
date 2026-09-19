<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5b39c8fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5b39c8fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:phone-call" {...props}></Icon>
