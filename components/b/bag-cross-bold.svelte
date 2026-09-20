<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oza3qgbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oza3qgbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-cross-bold" {...props}></Icon>
