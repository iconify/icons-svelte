<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9gam0boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y9gam0boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-infinite-loop-flat" {...props}></Icon>
