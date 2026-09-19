<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpbmd6afz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpbmd6afz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:night-light" {...props}></Icon>
