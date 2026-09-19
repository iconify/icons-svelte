<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9xb2qb7w.css';
import '../../css/g/gdngdpbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="y9xb2qb7w"/><path class="gdngdpbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:arduino" {...props}></Icon>
