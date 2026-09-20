<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii0t0frbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ii0t0frbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:button-fast-forward-2-flat" {...props}></Icon>
