<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/autq6ssyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="autq6ssyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-pin" {...props}></Icon>
