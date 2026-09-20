<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_fte1kzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_fte1kzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:lifebuoy-fill" {...props}></Icon>
