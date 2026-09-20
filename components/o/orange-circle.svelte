<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="y-jqxs3dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:orange-circle" {...props}></Icon>
<style>
:global(.y-jqxs3dx) {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--f4900c, #f4900c);
}

</style>
