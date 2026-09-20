<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dv09d5sem"><path class="gstkoq_-e"/><path class="t5d7j4bxz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:aleo" {...props}></Icon>
<style>
:global(.dv09d5sem) {
  fill: var(--svg-color--111, #111);
}

:global(.gstkoq_-e) {
  d: path("M14.13 3h-3.97L6.715 13.523h2.098l2.79-8.585h1.011l2.791 8.585H8.813l-.65 1.939h7.868L17.835 21H20z");
}

:global(.t5d7j4bxz) {
  d: path("M4.266 21h2.093l1.805-5.538H6.08zm.369-7.477L4 15.462h2.08l.635-1.939z");
}

</style>
