<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be5dz-b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="be5dz-b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:navigation-arrow-north-solid" {...props}></Icon>
