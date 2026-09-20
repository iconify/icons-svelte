<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/uiwsg29tk.css';
import '../../css/q/qrqz59bvc.css';
import '../../css/o/opk43_ukr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uiwsg29tk"/><path class="qrqz59bvc"/><path class="opk43_ukr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bill-cross-broken" {...props}></Icon>
