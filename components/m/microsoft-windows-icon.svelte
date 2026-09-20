<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="wh0rmpb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:microsoft-windows-icon" {...props}></Icon>
<style>
:global(.wh0rmpb7p) {
  fill: var(--svg-color--0078d4, #0078d4);
  d: path("M0 0h121.329v121.329H0zm134.671 0H256v121.329H134.671zM0 134.671h121.329V256H0zm134.671 0H256V256H134.671z");
}

</style>
