<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a42s6sbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a42s6sbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:fragile-solid" {...props}></Icon>
