<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y38x4ibjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y38x4ibjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-woman-curly-gloss" {...props}></Icon>
