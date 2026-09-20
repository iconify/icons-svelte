<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="rt-zdmbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:componentkit" {...props}></Icon>
<style>
:global(.rt-zdmbqk) {
  fill: var(--svg-color--39bcd3, #39bcd3);
  d: path("m92.748 135.605l77.82 77.82L127.991 256l-77.82-77.82zm120.677-50.188L256 127.992l-77.82 77.82l-42.575-42.575zM128.008 0l42.575 42.575L42.575 170.583L0 128.008z");
}

</style>
