<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9frh8pyw.css';
import '../../css/i/i2fpxzbyu.css';
import '../../css/z/z8_xk9jlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n9frh8pyw"/><path class="i2fpxzbyu"/><path class="z8_xk9jlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lightning-protection-48-bold" {...props}></Icon>
