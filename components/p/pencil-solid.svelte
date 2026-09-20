<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mte9jlnvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mte9jlnvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:pencil-solid" {...props}></Icon>
