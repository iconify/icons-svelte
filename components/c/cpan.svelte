<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weomk1dpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="weomk1dpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:cpan" {...props}></Icon>
