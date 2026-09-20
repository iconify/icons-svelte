<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="pi2g5bq9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:blue-circle" {...props}></Icon>
<style>
:global(.pi2g5bq9h) {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--55acee, #55acee);
}

</style>
