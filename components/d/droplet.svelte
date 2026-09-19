<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="iozrvmbhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:droplet" {...props}></Icon>
<style>
:global(.iozrvmbhw) {
  fill: var(--svg-color--75d6ff, #75d6ff);
  d: path("M32 2C20.6 17.6 14 32 14 43.8c0 10 8.1 18.2 18 18.2s18-8.1 18-18.2C50 32 43.2 17.4 32 2");
}

</style>
