<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0f10gbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z0f10gbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:r" {...props}></Icon>
