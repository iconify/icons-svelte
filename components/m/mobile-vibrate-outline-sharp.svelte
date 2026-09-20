<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx_qbnb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:mobile-vibrate-outline-sharp" {...props}></Icon>
<style>
:global(.wx_qbnb7y) {
  fill: currentColor;
  d: path("M1.462 14.5v-5h1v5zm2.769 2v-9h1v9zm17.307-2v-5h1v5zm-2.769 2v-9h1v9zM6.808 20V4h10.384v16zm9.384-1V5H7.808v14zM12.588 8.086q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22M7.808 5v14z");
}

</style>
