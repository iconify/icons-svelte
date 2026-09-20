<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef0a_xk9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef0a_xk9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:rakuten-kobo" {...props}></Icon>
