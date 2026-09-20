<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-2i7nb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-2i7nb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-offset-bottom-sharp-fill" {...props}></Icon>
