<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loibicc8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="loibicc8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-top-close-sharp" {...props}></Icon>
