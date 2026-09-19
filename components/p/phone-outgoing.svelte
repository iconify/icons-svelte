<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b--bnpbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b--bnpbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:phone-outgoing" {...props}></Icon>
