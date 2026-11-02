<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrh45udrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qrh45udrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:circle-half-full-20-solid" {...props}></Icon>
