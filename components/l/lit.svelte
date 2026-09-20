<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lurbt5era.css';
import '../../css/l/layi-mb4r.css';
import '../../css/k/ks9c86i1m.css';
import '../../css/c/cwafcrynf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":320};
const content = `<path class="lurbt5era"/><path class="layi-mb4r"/><path class="ks9c86i1m"/><path class="cwafcrynf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lit" {...props}></Icon>
