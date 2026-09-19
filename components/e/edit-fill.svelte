<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noj_8dt1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="noj_8dt1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:edit-fill" {...props}></Icon>
