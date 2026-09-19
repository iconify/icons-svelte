<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fjr0c7bie.css';
import '../../css/m/md286fbip.css';
import '../../css/t/td3thuy1e.css';
import '../../css/t/t9ubb0kvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="fjr0c7bie"/><g class="md286fbip"><path class="td3thuy1e"/><path class="t9ubb0kvl"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:ht" {...props}></Icon>
