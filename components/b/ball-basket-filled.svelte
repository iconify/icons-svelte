<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tudti3b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tudti3b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ball-basket-filled" {...props}></Icon>
