<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="os-o39pjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:android-cell-dual-4-bar-outline" {...props}></Icon>
<style>
:global(.os-o39pjc) {
  fill: currentColor;
  d: path("M2.866 14.962V9.923h1.692v5.039zm5.519 0V8.616h1.692v6.346zm5.519 0V6.789h1.692v8.173zm5.519 0V5h1.693v9.962zM2.866 19v-2.577h1.692V19zm5.519 0v-2.577h1.692V19zm5.519 0v-2.577h1.692V19zm5.519 0v-2.577h1.693V19z");
}

</style>
