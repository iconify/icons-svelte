<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbu-gbckp.css';
import '../../css/t/t9c8c1b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xbu-gbckp"/><path class="t9c8c1b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-open-20" {...props}></Icon>
