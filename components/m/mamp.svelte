<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crb39fbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crb39fbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mamp" {...props}></Icon>
