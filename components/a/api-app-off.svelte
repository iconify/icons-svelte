<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0ksiz2gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0ksiz2gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:api-app-off" {...props}></Icon>
