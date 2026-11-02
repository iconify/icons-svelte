<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aftbhrera.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aftbhrera"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-fork-line" {...props}></Icon>
