<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7t8u3biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d7t8u3biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:blackberry-logo-solid" {...props}></Icon>
