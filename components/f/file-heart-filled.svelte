<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hshhqwbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hshhqwbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-heart-filled" {...props}></Icon>
