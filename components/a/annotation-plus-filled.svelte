<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrz2ljobp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrz2ljobp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:annotation-plus-filled" {...props}></Icon>
