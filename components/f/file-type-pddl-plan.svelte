<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l83f5-b4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-pddl-plan" {...props}></Icon>
<style>
:global(.l83f5-b4x) {
  fill: var(--svg-color--green, green);
  d: path("M4.178 4.956h17.37v6.45H4.178zm7.145 8.538h17.37v6.45h-17.37zm10.334 8.539h7.036v6.45h-7.036z");
}

</style>
