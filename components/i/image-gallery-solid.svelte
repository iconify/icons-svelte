<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcpzljbeb.css';
import '../../css/j/jn9mjsb2g.css';
import '../../css/o/o9sdgwbjd.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="bcpzljbeb clr-i-solid clr-i-solid-path-1"/><path class="clr-i-solid clr-i-solid-path-2 jn9mjsb2g"/><path class="clr-i-solid clr-i-solid-path-3 o9sdgwbjd"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:image-gallery-solid" {...props}></Icon>
