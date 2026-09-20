<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7uw_y9fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h7uw_y9fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-ai-fill" {...props}></Icon>
