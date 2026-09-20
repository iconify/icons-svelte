<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er9fuob6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er9fuob6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-verify" {...props}></Icon>
