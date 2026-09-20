<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg6uzp21k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg6uzp21k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-plus" {...props}></Icon>
