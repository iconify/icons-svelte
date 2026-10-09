<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onr3s4yih.css';
import '../../css/v/vc5zz0hzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="onr3s4yih"/><path class="vc5zz0hzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-48-bold" {...props}></Icon>
