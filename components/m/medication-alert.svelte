<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfm1etoml.css';
import '../../css/t/tg8jb6oai.css';
import '../../css/f/fdrpmfhbn.css';
import '../../css/o/og4dv3brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mfm1etoml"/><path class="tg8jb6oai"/><circle class="fdrpmfhbn"/><path class="og4dv3brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:medication-alert" {...props}></Icon>
