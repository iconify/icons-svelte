<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovyxaofbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovyxaofbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:remove-1" {...props}></Icon>
