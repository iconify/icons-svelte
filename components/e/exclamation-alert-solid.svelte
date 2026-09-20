<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2vvmdmrt.css';
import '../../css/k/knuihczfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2vvmdmrt"/><path class="knuihczfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:exclamation-alert-solid" {...props}></Icon>
