<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o52kqiium.css';
import '../../css/k/kcinj1bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o52kqiium"/><path class="kcinj1bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oauth2-proxy-dark" {...props}></Icon>
