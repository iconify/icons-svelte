<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0wuxkb3p.css';
import '../../css/s/s-8c-vb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d0wuxkb3p"/><path class="s-8c-vb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:picnic-48-bold" {...props}></Icon>
