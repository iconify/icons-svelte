<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbjam7ssf.css';
import '../../css/h/h-k00lbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbjam7ssf"/><path class="h-k00lbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:copy-duotone" {...props}></Icon>
