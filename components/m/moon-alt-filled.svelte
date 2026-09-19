<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzr7y9y0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzr7y9y0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:moon-alt-filled" {...props}></Icon>
