<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pas3bn7jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pas3bn7jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:info-square-filled" {...props}></Icon>
