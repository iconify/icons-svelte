<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw6ppgbbn.css';
import '../../css/w/wf_7x7bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nw6ppgbbn"/><path class="wf_7x7bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:config-typescript" {...props}></Icon>
