<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2k121bbm.css';
import '../../css/c/c28fqubye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2k121bbm"/><path class="c28fqubye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rotate-cw-dot-filled" {...props}></Icon>
