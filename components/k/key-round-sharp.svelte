<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juvi3mbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juvi3mbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:key-round-sharp" {...props}></Icon>
