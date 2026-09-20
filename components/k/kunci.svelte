<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk928bc6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk928bc6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kunci" {...props}></Icon>
