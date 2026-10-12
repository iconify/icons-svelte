<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6j4wovga.css';
import '../../css/g/gcy3r1rbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a6j4wovga"/><path class="gcy3r1rbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:building-complex-filled" {...props}></Icon>
