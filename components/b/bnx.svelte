<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrsmjybvs.css';
import '../../css/t/tc0ligbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrsmjybvs"/><path class="tc0ligbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bnx" {...props}></Icon>
