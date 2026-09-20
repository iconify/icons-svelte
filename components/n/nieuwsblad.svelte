<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bocw3lbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nieuwsblad" {...props}></Icon>
<style>
:global(.bocw3lbzv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 7.748H27.348v6.96h3.282v11.745L21.29 9.756a3.92 3.92 0 0 0-3.423-2.008H5.5v6.96h3.294v18.583H5.5v6.96h15.152v-6.96H17.37V21.547l9.34 16.697a3.92 3.92 0 0 0 3.423 2.008h9.073V14.709H42.5z");
}

</style>
