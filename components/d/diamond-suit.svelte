<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snp287xku.css';
import '../../css/p/pp8nmdb7j.css';
import '../../css/k/k5loyzbkf.css';
import '../../css/w/w5u46jbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="snp287xku"/><path class="pp8nmdb7j"/><path class="k5loyzbkf"/><path class="w5u46jbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-emojis:diamond-suit" {...props}></Icon>
