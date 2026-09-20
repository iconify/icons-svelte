<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpjr9ccpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:account-balance-sharp" {...props}></Icon>
<style>
:global(.cpjr9ccpk) {
  fill: currentColor;
  d: path("M6.5 17V9h1v8zm5 0V9h1v8zm-7.961 3v-1h16.923v1zM16.5 17V9h1v8zM3.539 7v-.846L12 2.116l8.462 4.038V7z");
}

</style>
