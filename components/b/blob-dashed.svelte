<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnyw0abwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnyw0abwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:blob-dashed" {...props}></Icon>
