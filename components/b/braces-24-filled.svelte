<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knswxh7kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:braces-24-filled" {...props}></Icon>
<style>
:global(.knswxh7kw) {
  fill: currentColor;
  d: path("M4 6a3 3 0 0 1 3-3a1 1 0 0 1 0 2a1 1 0 0 0-1 1v3.938c0 .789-.307 1.519-.82 2.062c.513.543.82 1.273.82 2.062V18a1 1 0 0 0 1 1a1 1 0 1 1 0 2a3 3 0 0 1-3-3v-3.938a1 1 0 0 0-.757-.97l-.486-.122a1 1 0 0 1 0-1.94l.486-.121A1 1 0 0 0 4 9.939zm16 0a3 3 0 0 0-3-3a1 1 0 1 0 0 2a1 1 0 0 1 1 1v3.938c0 .789.307 1.519.82 2.062a3 3 0 0 0-.82 2.062V18a1 1 0 0 1-1 1a1 1 0 1 0 0 2a3 3 0 0 0 3-3v-3.938a1 1 0 0 1 .758-.97l.485-.122a1 1 0 0 0 0-1.94l-.485-.121a1 1 0 0 1-.758-.97z");
}

</style>
