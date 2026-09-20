<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t639_obhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t639_obhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:envelope-lock" {...props}></Icon>
