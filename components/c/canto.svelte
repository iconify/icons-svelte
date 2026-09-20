<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klr2g0esj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:canto" {...props}></Icon>
<style>
:global(.klr2g0esj) {
  fill: var(--svg-color--74f8a2, #74f8a2);
  d: path("M6.536 3h14.142v18H6.536v-3.214H3.32V6.214h3.215zm10.928 3.214H9.75V9.43H6.536v5.143H9.75v3.214h7.714V14.57H9.75V9.43h7.714z");
}

</style>
