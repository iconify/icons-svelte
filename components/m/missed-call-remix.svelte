<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqfbs9a5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uqfbs9a5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:missed-call-remix" {...props}></Icon>
