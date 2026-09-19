<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6242fb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6242fb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-new" {...props}></Icon>
