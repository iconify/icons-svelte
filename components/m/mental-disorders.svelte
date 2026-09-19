<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muk07ebbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="muk07ebbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:mental-disorders" {...props}></Icon>
