<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrr7wkbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrr7wkbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mug" {...props}></Icon>
