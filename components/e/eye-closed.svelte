<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byy2t7i3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byy2t7i3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:eye-closed" {...props}></Icon>
