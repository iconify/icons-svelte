<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hk79asbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:eurt" {...props}></Icon>
<style>
:global(.hk79asbxz) {
  fill: var(--svg-color--fff, #fff);
  d: path("M9 17.4h10.2V21H4.8V3h13.8v3.6H9v3.6h9v3.6H9z");
}

</style>
