<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejyw6md3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejyw6md3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:caret-right-outline" {...props}></Icon>
