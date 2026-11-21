<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4flwc34c.css';
import '../../css/p/pyu-_y9kf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4flwc34c"/><path class="pyu-_y9kf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-check-filled" {...props}></Icon>
