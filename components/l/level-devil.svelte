<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z_vrnwpaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:level-devil" {...props}></Icon>
<style>
:global(.z_vrnwpaf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.01 5.5v9.336h-6.53v13.696h3.062v5.927H8.917v6.506h14.647v-3.131h9.439V42.5h6.08V31.389h-6.286V14.836H29.37V5.5z");
}

</style>
