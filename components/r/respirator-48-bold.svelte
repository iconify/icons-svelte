<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsw62-7zd.css';
import '../../css/i/iib416bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bsw62-7zd"/><path class="iib416bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:respirator-48-bold" {...props}></Icon>
