<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5ivu1cqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:javascript-outline-sharp" {...props}></Icon>
<style>
:global(.r5ivu1cqv) {
  fill: currentColor;
  d: path("M6.23 14.692V12.5h.886v1.308h2.076v-4.5h.885v5.384zm6.078 0V13h.884v.808h2.616v-1.5h-3.5v-3h4.384V11h-.884v-.808h-2.616v1.5h3.5v3z");
}

</style>
