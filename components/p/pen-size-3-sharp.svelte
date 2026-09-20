<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hylzzpbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:pen-size-3-sharp" {...props}></Icon>
<style>
:global(.hylzzpbii) {
  fill: currentColor;
  d: path("M5.45 18.55q-.425-.425-.425-1.05t.425-1.05l11-11q.425-.45 1.05-.438t1.05.438t.438 1.05t-.438 1.05l-11 11q-.425.425-1.05.438t-1.05-.438");
}

</style>
