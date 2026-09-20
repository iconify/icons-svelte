<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajres5ior.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajres5ior"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:heart-question" {...props}></Icon>
