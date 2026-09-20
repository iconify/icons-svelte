<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2e3knbpj.css';
import '../../css/n/n38mbh-2w.css';
import '../../css/l/lm2ism19n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o2e3knbpj"/><path class="n38mbh-2w"/><path class="lm2ism19n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:metatana" {...props}></Icon>
