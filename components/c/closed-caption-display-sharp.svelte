<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlxlsabml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:closed-caption-display-sharp" {...props}></Icon>
<style>
:global(.mlxlsabml) {
  fill: currentColor;
  d: path("M12.327 21v-6.115H21V21zm1-1H20v-4.115h-6.673zM4 19V5h16v7.5h-6.192v-2.308h2.615v.616h.885v-1.5h-4.385v3.384h-2.98v1.116H7.576v-3.616h2.615v.616h.885v-1.5H6.692v5.384h3.25V19z");
}

</style>
