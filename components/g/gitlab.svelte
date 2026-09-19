<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyrvhrl1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tyrvhrl1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:gitlab" {...props}></Icon>
