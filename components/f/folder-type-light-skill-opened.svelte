<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ia_jvxbqb"/><path class="ry21rrbyl"/><path class="iuldd65qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:folder-type-light-skill-opened" {...props}></Icon>
<style>
:global(.ia_jvxbqb) {
  fill: var(--svg-color--585858, #585858);
  d: path("M29.5 5.5H18.2l-2.1 4.2H4.3v16.8h25.2zm-2.1 18.7H6.6V11.8h20.8zm0-14.5h-8.2l1-2.1h7.1zm-1.7 4H.5l3.8 12.8h25.2z");
}

:global(.iuldd65qy) {
  stroke: var(--svg-color--fff, #fff);
  stroke-width: var(--svg-stroke-width--2-032px, 2.032px);
  d: path("m21.91 13.73l5.86 3.38v6.78l-5.86 3.38l-5.87-3.38v-6.78z");
}

:global(.ry21rrbyl) {
  d: path("M21.91 10L31 15.25v10.5L21.91 31l-9.09-5.25v-10.5z");
}

</style>
