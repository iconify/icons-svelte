<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cobpw81wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cobpw81wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ball-pen-fill" {...props}></Icon>
