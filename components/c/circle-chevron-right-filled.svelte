<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf_-qtb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf_-qtb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-chevron-right-filled" {...props}></Icon>
