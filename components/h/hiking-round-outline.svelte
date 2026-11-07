<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2c1ynjwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c2c1ynjwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hiking-round-outline" {...props}></Icon>
