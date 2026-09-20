<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypbhdv3qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:float-landscape" {...props}></Icon>
<style>
:global(.ypbhdv3qw) {
  fill: currentColor;
  d: path("M17 20v-7h5v7h-5ZM4 20q-.825 0-1.413-.588T2 18V6q0-.825.588-1.413T4 4h16q.825 0 1.413.588T22 6v5h-7v9H4Z");
}

</style>
