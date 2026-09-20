<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wywn09brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wywn09brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:menu-deep" {...props}></Icon>
