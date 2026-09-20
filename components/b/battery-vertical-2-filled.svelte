<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7w_-bb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7w_-bb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-vertical-2-filled" {...props}></Icon>
