<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pocy658dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:attack-chain" {...props}></Icon>
<style>
:global(.pocy658dn) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.465 6.293l2.828-2.828q.878-.879 2.121-.879t2.121.879q.879.878.879 2.121t-.879 2.121l-2.828 2.828q-.603.604-1.379.793q-.189.776-.793 1.379l-2.828 2.828q-.603.604-1.379.793q-.189.776-.793 1.379l-2.828 2.828q-.878.879-2.121.879t-2.121-.879q-.879-.878-.879-2.121t.879-2.121l2.828-2.828q.603-.604 1.379-.793q.189-.776.793-1.379l2.828-2.828q.603-.604 1.379-.793q.189-.776.793-1.379");
}

</style>
