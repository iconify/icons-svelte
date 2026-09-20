<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7062bdzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7062bdzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:emotion-add-fill" {...props}></Icon>
