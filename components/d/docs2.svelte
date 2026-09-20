<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2e7xuh9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h2e7xuh9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:docs2" {...props}></Icon>
