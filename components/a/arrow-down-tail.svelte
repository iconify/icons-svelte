<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bluom-brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bluom-brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-down-tail" {...props}></Icon>
