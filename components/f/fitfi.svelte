<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rys5o5b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rys5o5b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fitfi" {...props}></Icon>
