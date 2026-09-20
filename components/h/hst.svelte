<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="df03pcb5b"/><path clip-rule="evenodd" class="f9r73xbgb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:hst" {...props}></Icon>
<style>
:global(.df03pcb5b) {
  fill: var(--svg-color--545eff, #545eff);
  d: path("M16.446 16.5C18.96 16.5 21 14.485 21 12s-2.04-4.5-4.554-4.5c-2.203 0-4.041 1.546-4.463 3.6H16.5a.9.9 0 0 1 0 1.8h-4.517c.422 2.054 2.26 3.6 4.463 3.6");
}

:global(.f9r73xbgb) {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M3.9 7.5a.9.9 0 0 0-.9.9v7.2a.9.9 0 0 0 .9.9h7.2a.9.9 0 0 0 .9-.9V8.4a.9.9 0 0 0-.9-.9zm8.098 3.6H8.32L6.6 12.9h5.398z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

</style>
