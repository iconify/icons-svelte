<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="y6zz06boa"/><path class="tmybsktkk"/></g><g class="y9tr6bcfx"><path class="ho7b1vb_c"/><path class="ibie-9bnp"/><path class="w0pn9f1nf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:notion-calendar-18" {...props}></Icon>
<style>
:global(.ho7b1vb_c) {
  d: path("m39.153 41.418l-24.717 1.08a2.97 2.97 0 0 1-3.097-2.966v-25.21a2.97 2.97 0 0 1 2.838-2.966l25.956-1.133a1.78 1.78 0 0 1 1.859 1.779v26.451a2.97 2.97 0 0 1-2.839 2.965");
}

:global(.ibie-9bnp) {
  d: path("M11.339 22.117v-2.97c0-.954.75-1.738 1.703-1.78l27.091-1.182a1.78 1.78 0 0 1 1.859 1.779v3.803");
}

:global(.tmybsktkk) {
  d: path("M31.555 28.86c1.76-.092 3.2-1.608 3.2-3.368s-1.44-3.124-3.2-3.032l-2.08.11c-1.76.091-3.2 1.607-3.2 3.367s1.44 3.124 3.2 3.032m-4.5 6.636l-6.4.336");
}

:global(.w0pn9f1nf) {
  d: path("M36.661 10.248V7.874a2.374 2.374 0 0 0-2.477-2.372L8.279 6.633a2.374 2.374 0 0 0-2.27 2.372v25.65a2.374 2.374 0 0 0 2.466 2.373l2.864-.112");
}

:global(.y6zz06boa) {
  d: path("m18.575 24.9l3.2-1.927m0 0v12.8m9.78-6.913l-2.08.11c-1.76.091-3.2 1.607-3.2 3.367s1.44 3.124 3.2 3.032l2.08-.109c1.76-.092 3.2-1.608 3.2-3.368s-1.44-3.124-3.2-3.032");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
