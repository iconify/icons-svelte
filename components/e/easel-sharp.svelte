<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7bg-j5tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7bg-j5tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:easel-sharp" {...props}></Icon>
