<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z72ipnvwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:borg-sharp" {...props}></Icon>
<style>
:global(.z72ipnvwi) {
  fill: currentColor;
  d: path("m11.5 20.783l-7.23-4.196V12.5h4.403v2.848H11.5zM4.27 11.5V7.414l7.23-4.197v5.435H8.673V11.5zm5.403 2.846V9.673h4.635v4.673zm2.827 6.437v-5.435h2.808V12.5h4.423v4.087zm2.808-9.283V8.652H12.5V3.217l7.23 4.197V11.5z");
}

</style>
