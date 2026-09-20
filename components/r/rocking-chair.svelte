<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkwno1bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkwno1bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rocking-chair" {...props}></Icon>
