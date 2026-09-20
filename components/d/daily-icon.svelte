<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":301};
const content = `<path class="z7kz7tbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:daily-icon" {...props}></Icon>
<style>
:global(.z7kz7tbxp) {
  d: path("M0 300.931V217.94L108.451 0H256v83.029L147.603 300.931z");
}

</style>
