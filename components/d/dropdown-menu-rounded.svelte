<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysti1lgso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:dropdown-menu-rounded" {...props}></Icon>
<style>
:global(.ysti1lgso) {
  fill: currentColor;
  d: path("m15.066 13.666l1.7-1.7q.192-.193.095-.445t-.369-.252h-3.984q-.272 0-.369.252t.096.445l1.7 1.7q.242.242.565.242t.566-.242M8 18q-2.507 0-4.253-1.745Q2 14.509 2 12.004t1.747-4.255T8 6h8q2.507 0 4.254 1.745T22 11.996t-1.747 4.255T16 18z");
}

</style>
