<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sibcf0bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sibcf0bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:pull-request" {...props}></Icon>
