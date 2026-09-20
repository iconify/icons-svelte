<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic2pnubyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ic2pnubyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:hot-spring-solid" {...props}></Icon>
