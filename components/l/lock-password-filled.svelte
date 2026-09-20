<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi68c0nhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oi68c0nhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lock-password-filled" {...props}></Icon>
