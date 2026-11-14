<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5mpe8bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:circles-intersect" {...props}></Icon>
<style>
:global(.l5mpe8bnb) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.727 7.227Q1.75 9.204 1.75 12t1.977 4.773T8.5 18.75q1.949 0 3.5-.961q1.551.961 3.5.961q2.796 0 4.773-1.977T22.25 12t-1.977-4.773T15.5 5.25q-1.949 0-3.5.961q-1.551-.961-3.5-.961q-2.796 0-4.773 1.977");
}

</style>
