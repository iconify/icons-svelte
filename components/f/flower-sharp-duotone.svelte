<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whw3bdb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whw3bdb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flower-sharp-duotone" {...props}></Icon>
