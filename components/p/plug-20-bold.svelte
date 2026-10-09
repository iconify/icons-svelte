<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt_zhw2mi.css';
import '../../css/i/i_3ks9poz.css';
import '../../css/q/qbyv8qirk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xt_zhw2mi"/><path class="i_3ks9poz"/><path class="qbyv8qirk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plug-20-bold" {...props}></Icon>
