<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6m0gsbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b6m0gsbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:logout-3-bold" {...props}></Icon>
