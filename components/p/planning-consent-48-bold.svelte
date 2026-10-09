<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frd-8-btx.css';
import '../../css/n/ngqac4bpf.css';
import '../../css/y/y9mg2tbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="frd-8-btx"/><path class="ngqac4bpf"/><path class="y9mg2tbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:planning-consent-48-bold" {...props}></Icon>
