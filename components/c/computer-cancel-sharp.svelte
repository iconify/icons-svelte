<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="su9lk5bnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:computer-cancel-sharp" {...props}></Icon>
<style>
:global(.su9lk5bnz) {
  fill: currentColor;
  d: path("m9.4 14.27l2.6-2.6l2.6 2.6l.708-.708l-2.6-2.6l2.6-2.6l-.708-.708l-2.6 2.6l-2.6-2.6l-.708.708l2.6 2.6l-2.6 2.6zm-7.63 5.192v-1h20.46v1zm1.23-2v-13h18v13z");
}

</style>
