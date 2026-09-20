<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brly5_bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:mobile-screensaver-outline-sharp" {...props}></Icon>
<style>
:global(.brly5_bhc) {
  fill: currentColor;
  d: path("M6 22V2h12.077v4.83H19v3.686h-.923V22zm1-1h10.077V3H7zm1.5-6.23h7.077l-2.144-2.886l-1.894 2.5l-1.395-1.844zm6.857-4.838q.22-.221.22-.549t-.221-.547t-.55-.22t-.547.221t-.22.549t.221.548t.549.22t.548-.222M7 21V3z");
}

</style>
