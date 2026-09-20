<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gom_4pbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:oxen" {...props}></Icon>
<style>
:global(.gom_4pbjc) {
  fill: var(--svg-color--12c6ba, #12c6ba);
  fill-rule: evenodd;
  d: path("M12 12L3 4.2h18zm0 0l-9 7.8h18z");
}

</style>
