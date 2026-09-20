<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9_oqkbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:lvl" {...props}></Icon>
<style>
:global(.e9_oqkbgn) {
  fill: var(--svg-color--ffb313, #ffb313);
  d: path("M4.161 3h5.807v4.065H4.16zm0 6.968h9.871v4.064h-9.87zm0 6.968H19.84V21H4.16z");
}

</style>
