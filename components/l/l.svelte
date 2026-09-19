<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3mh3qbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":754};
const content = `<path class="s3mh3qbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:l" {...props}></Icon>
