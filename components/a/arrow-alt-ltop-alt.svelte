<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bud6u-kad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bud6u-kad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arrow-alt-ltop-alt" {...props}></Icon>
