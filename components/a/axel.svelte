<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecy74ybpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecy74ybpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:axel" {...props}></Icon>
