<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crdvqi0ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="crdvqi0ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:path" {...props}></Icon>
