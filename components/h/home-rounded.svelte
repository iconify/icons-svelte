<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svdexnquw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svdexnquw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:home-rounded" {...props}></Icon>
