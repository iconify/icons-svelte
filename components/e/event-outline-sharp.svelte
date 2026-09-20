<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3j773g3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:event-outline-sharp" {...props}></Icon>
<style>
:global(.c3j773g3p) {
  fill: currentColor;
  d: path("M13.389 17.38q-.62-.618-.62-1.495t.62-1.496t1.496-.62q.877 0 1.496.62T17 15.885t-.62 1.496t-1.495.619t-1.496-.62M4 21V5h3.385V2.77h1.077V5h7.154V2.77h1V5H20v16zm1-1h14v-9.384H5zM5 9.615h14V6H5zm0 0V6z");
}

</style>
