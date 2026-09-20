<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3uu33gcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:on-hub-device-sharp" {...props}></Icon>
<style>
:global(.n3uu33gcr) {
  fill: currentColor;
  d: path("M8.923 19.77v-1h6.154v1zm0-2.77L7.902 4h8.196l-1.021 13z");
}

</style>
