<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdc4-_bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdc4-_bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:profile" {...props}></Icon>
