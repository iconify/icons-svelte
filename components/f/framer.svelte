<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":384};
const content = `<path class="cm1oe6iah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:framer" {...props}></Icon>
<style>
:global(.cm1oe6iah) {
  d: path("M0 0h256v128H128zm0 128h128l128 128H128v128L0 256z");
}

</style>
