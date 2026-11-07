<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3h3pubhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s3h3pubhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-5-bold" {...props}></Icon>
