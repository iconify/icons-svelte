<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du55pnb9m.css';
import '../../css/o/od1iqpboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="du55pnb9m"/><path class="od1iqpboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:image-layout-thumbnail" {...props}></Icon>
