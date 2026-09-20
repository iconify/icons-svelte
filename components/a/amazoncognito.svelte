<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6aym8bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6aym8bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amazoncognito" {...props}></Icon>
