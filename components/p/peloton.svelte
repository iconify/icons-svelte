<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezcex-blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezcex-blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:peloton" {...props}></Icon>
