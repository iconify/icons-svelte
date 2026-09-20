<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kvm_u3h-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:circle" {...props}></Icon>
<style>
:global(.kvm_u3h-v) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 5.5a4.5 4.5 0 1 0 0 9a4.5 4.5 0 0 0 0-9M3.5 10a6.5 6.5 0 1 1 13 0a6.5 6.5 0 0 1-13 0");
}

</style>
