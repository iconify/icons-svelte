<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjv3jqbyi.css';
import '../../css/q/qylci8b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cjv3jqbyi"/><path class="qylci8b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:gift-card" {...props}></Icon>
