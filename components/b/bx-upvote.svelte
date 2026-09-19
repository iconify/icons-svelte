<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aajt7uejw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aajt7uejw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-upvote" {...props}></Icon>
