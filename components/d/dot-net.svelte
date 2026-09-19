<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5rupt_8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="v5rupt_8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:dot-net" {...props}></Icon>
