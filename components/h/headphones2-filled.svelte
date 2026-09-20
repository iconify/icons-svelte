<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia4gr-z1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia4gr-z1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:headphones2-filled" {...props}></Icon>
