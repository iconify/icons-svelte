<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an64b99yj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="an64b99yj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:krom" {...props}></Icon>
