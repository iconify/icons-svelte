<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_pr9ks0t.css';
import '../../css/c/czhl_6b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_pr9ks0t"/><path class="czhl_6b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:image-file-star-bold" {...props}></Icon>
