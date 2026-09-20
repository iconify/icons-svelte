<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htg1gvych.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htg1gvych"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-box-right-middle-filled" {...props}></Icon>
