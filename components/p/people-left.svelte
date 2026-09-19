<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6okt_aby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f6okt_aby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:people-left" {...props}></Icon>
