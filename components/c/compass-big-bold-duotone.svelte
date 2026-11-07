<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn-nc5ohr.css';
import '../../css/z/z5mu4-byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kn-nc5ohr"/><path class="z5mu4-byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:compass-big-bold-duotone" {...props}></Icon>
