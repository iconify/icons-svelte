<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufxac6bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufxac6bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:background" {...props}></Icon>
