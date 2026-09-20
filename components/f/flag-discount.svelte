<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzj8564wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzj8564wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-discount" {...props}></Icon>
