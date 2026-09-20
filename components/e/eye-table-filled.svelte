<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5qah2bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5qah2bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:eye-table-filled" {...props}></Icon>
