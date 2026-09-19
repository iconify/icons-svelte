<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3fqakbcn.css';
import '../../css/s/s3i81qbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u3fqakbcn"/><path class="s3i81qbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:right-up" {...props}></Icon>
