<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4-1j-bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4-1j-bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:annotation-text-filled" {...props}></Icon>
