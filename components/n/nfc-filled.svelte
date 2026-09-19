<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm0a7yn5d.css';
import '../../css/s/su784c8yq.css';
import '../../css/x/xot3z3mcu.css';
import '../../css/l/lahk8gn4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm0a7yn5d"/><path class="su784c8yq"/><path class="xot3z3mcu"/><path class="lahk8gn4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:nfc-filled" {...props}></Icon>
