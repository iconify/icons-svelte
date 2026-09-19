<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-nva6oky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-nva6oky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:layout-align-top" {...props}></Icon>
