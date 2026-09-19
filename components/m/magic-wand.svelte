<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7_kk0ivj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l7_kk0ivj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:magic-wand" {...props}></Icon>
