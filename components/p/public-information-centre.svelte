<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlji710lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:public-information-centre" {...props}></Icon>
<style>
:global(.dlji710lc) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 19.25v-8.385q0-1.235.981-1.986l6.75-5.162q1.519-1.161 3.038 0l6.75 5.162q.981.751.981 1.986v8.385q0 1.036-.732 1.768t-1.768.732H5.25q-1.036 0-1.768-.732T2.75 19.25");
}

</style>
