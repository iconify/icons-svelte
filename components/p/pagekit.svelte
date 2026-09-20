<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":320};
const content = `<path class="modbayy2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:pagekit" {...props}></Icon>
<style>
:global(.modbayy2a) {
  fill: var(--svg-color--212121, #212121);
  d: path("M0 0v320h128v-48H48V45.333h160V224h-80v48h128V0z");
}

</style>
