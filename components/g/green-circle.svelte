<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="s7lk2nbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:green-circle" {...props}></Icon>
<style>
:global(.s7lk2nbec) {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--78b159, #78b159);
}

</style>
