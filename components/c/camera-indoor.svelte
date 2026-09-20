<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq1mxzm8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:camera-indoor" {...props}></Icon>
<style>
:global(.bq1mxzm8q) {
  fill: currentColor;
  d: path("M5 20V9.5l7-5.27l7 5.27V20zm4.154-3.384h4q.262 0 .438-.177q.177-.177.177-.439v-1.461l1.846.972V12.49l-1.846.973V12q0-.261-.177-.438t-.438-.177h-4q-.262 0-.438.177q-.177.177-.177.438v4q0 .262.177.439q.176.177.438.177");
}

</style>
