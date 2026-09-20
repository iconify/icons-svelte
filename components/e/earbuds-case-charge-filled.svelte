<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk_s2sw1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pk_s2sw1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:earbuds-case-charge-filled" {...props}></Icon>
