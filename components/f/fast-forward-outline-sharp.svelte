<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2gkpt2sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:fast-forward-outline-sharp" {...props}></Icon>
<style>
:global(.q2gkpt2sy) {
  fill: currentColor;
  d: path("M4.096 16.616V7.385L11.02 12zm8.885 0V7.385L19.904 12zM5.096 14.75L9.227 12l-4.13-2.75zm8.885 0L18.11 12l-4.13-2.75z");
}

</style>
