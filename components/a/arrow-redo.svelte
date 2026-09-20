<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg5skcb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg5skcb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:arrow-redo" {...props}></Icon>
