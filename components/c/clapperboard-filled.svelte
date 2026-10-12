<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stk6y9nje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="stk6y9nje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clapperboard-filled" {...props}></Icon>
