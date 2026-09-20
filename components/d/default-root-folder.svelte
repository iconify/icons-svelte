<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zghy_mbjo"/><path class="jxzdurb2m"/><path class="qlahy-byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:default-root-folder" {...props}></Icon>
<style>
:global(.jxzdurb2m) {
  fill: var(--svg-color--c09553, #c09553);
  d: path("M19.735 31.25h-5.924l9.794-21.5h5.985z");
}

:global(.qlahy-byj) {
  fill: var(--svg-color--ffeebe, #ffeebe);
  d: path("M23.766 10H29.2l-9.625 21H14.2Z");
}

:global(.zghy_mbjo) {
  fill: var(--svg-color--c09553, #c09553);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

</style>
