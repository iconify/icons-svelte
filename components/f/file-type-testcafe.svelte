<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lsljf5b6l"/><path class="qla7mebyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-testcafe" {...props}></Icon>
<style>
:global(.lsljf5b6l) {
  fill: var(--svg-color--36b6e5, #36b6e5);
  d: path("M28.115 9.432L25.701 7L15.562 17.216L11.7 13.324l-2.413 2.433l6.275 6.324z");
}

:global(.qla7mebyf) {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("m19.425 19.151l-1.194 1.05h4.181l3.584 3.299H5.986l3.584-3.299h3.136l-1.045-1.05H8.824L2 25h28l-6.841-5.849z");
}

</style>
