<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zstkoeogs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zstkoeogs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:online-learning-01" {...props}></Icon>
