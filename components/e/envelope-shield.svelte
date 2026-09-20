<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7a_1ab1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7a_1ab1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:envelope-shield" {...props}></Icon>
