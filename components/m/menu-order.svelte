<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bco-2qu9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bco-2qu9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:menu-order" {...props}></Icon>
