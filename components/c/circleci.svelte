<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riyh8pbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":505,"height":512};
const content = `<path class="riyh8pbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:circleci" {...props}></Icon>
