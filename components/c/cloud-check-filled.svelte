<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4flwc34c.css';
import '../../css/a/ateqv7i3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4flwc34c"/><path class="ateqv7i3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-check-filled" {...props}></Icon>
