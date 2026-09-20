<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ujzigvbth"/><path class="s7ss5e_ih"/><path class="bvo_uyfuo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:algb" {...props}></Icon>
<style>
:global(.bvo_uyfuo) {
  fill: var(--svg-color--5d32ed, #5d32ed);
  d: path("m12 15.442l-8.735 5.03h17.47z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.s7ss5e_ih) {
  fill: var(--svg-color--00cab2, #00cab2);
  d: path("M12.265 3.529V14.91L21 19.941z");
}

:global(.ujzigvbth) {
  fill: var(--svg-color--b41870, #b41870);
  d: path("M11.735 3.529V14.91L3 19.941z");
}

</style>
