<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u970n0bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u970n0bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:banknote-2-x-sharp" {...props}></Icon>
