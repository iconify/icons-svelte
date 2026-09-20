<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md1qd5bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="md1qd5bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:password-pencil-16-solid" {...props}></Icon>
