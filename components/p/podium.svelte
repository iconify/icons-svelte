<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0mgzh53n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0mgzh53n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:podium" {...props}></Icon>
