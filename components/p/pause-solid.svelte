<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea7vas5oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea7vas5oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pause-solid" {...props}></Icon>
