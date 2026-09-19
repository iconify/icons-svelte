<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3wypyb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":512};
const content = `<path class="s3wypyb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:leaf" {...props}></Icon>
