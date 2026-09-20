<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhr_0nbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:markunread-mailbox-outline-sharp" {...props}></Icon>
<style>
:global(.xhr_0nbrx) {
  fill: currentColor;
  d: path("M6 14v-4H4v10h16V10H10V8h12v14H2V8h4V2h8v4H8v8zm-2-4v4zv10z");
}

</style>
