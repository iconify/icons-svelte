<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tajw0vbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mobile-lock-landscape-outline-sharp" {...props}></Icon>
<style>
:global(.tajw0vbam) {
  fill: currentColor;
  d: path("M9 16h6v-5h-1v-1q0-.825-.587-1.412T12 8t-1.412.588T10 10v1H9zm2-5v-1q0-.425.288-.712T12 9t.713.288T13 10v1zM1 19V5h5.1V4h4.8v1H23v14zm20-2V7H3v10zM3 17V7z");
}

</style>
