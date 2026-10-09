<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkestgbmb.css';
import '../../css/k/kc-33db0z.css';
import '../../css/w/wdh6v20fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nkestgbmb"/><path class="kc-33db0z"/><path class="wdh6v20fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-boiler-20" {...props}></Icon>
