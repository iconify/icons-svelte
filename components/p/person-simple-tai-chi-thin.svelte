<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="y-b50vv8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:person-simple-tai-chi-thin" {...props}></Icon>
<style>
:global(.y-b50vv8p) {
  fill: currentColor;
  d: path("M128 76a28 28 0 1 0-28-28a28 28 0 0 0 28 28m0-48a20 20 0 1 1-20 20a20 20 0 0 1 20-20m92 76a4 4 0 0 1-4 4h-84v33.36l53.58 23A4 4 0 0 1 188 168v48a4 4 0 0 1-8 0v-45.36l-51.22-22L50.68 219a4 4 0 1 1-5.36-6L124 142.22V108H40a4 4 0 0 1 0-8h176a4 4 0 0 1 4 4");
}

</style>
