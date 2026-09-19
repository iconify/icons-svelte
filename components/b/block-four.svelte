<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyk46-7ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jyk46-7ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:block-four" {...props}></Icon>
