<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zpnc8pbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-shadcn" {...props}></Icon>
<style>
:global(.zpnc8pbvy) {
  stroke: var(--svg-color--dedede, #dedede);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--4-48px, 4.48px);
  d: path("m27.76 16.56l-11.2 11.2m8.96-23.52L4.24 25.52");
}

</style>
