<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m0k48-ieh"/><path class="rwk616f6k"/><path class="tune_acvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-light-hashicorp" {...props}></Icon>
<style>
:global(.m0k48-ieh) {
  d: path("m13.8 2l-11 6.3v15.4L6.9 26V10.7l6.9-4z");
}

:global(.rwk616f6k) {
  d: path("M18.2 2v12.2h-4.4V9.7L9.7 12v15.6l4.1 2.4V17.9h4.4v4.4l4.1-2.3V4.4z");
}

:global(.tune_acvv) {
  d: path("m18.2 30l11-6.3V8.3L25.1 6v15.3l-6.9 4z");
}

</style>
