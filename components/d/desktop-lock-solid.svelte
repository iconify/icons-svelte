<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knamxxb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="knamxxb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:desktop-lock-solid" {...props}></Icon>
