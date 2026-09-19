<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvcq89ble.css';
import '../../css/g/gwcu8infc.css';
import '../../css/w/wnfssjrql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cvcq89ble"><path class="gwcu8infc"/><path class="wnfssjrql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:npm-ignore" {...props}></Icon>
