<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGyYQWPcRW)" class="qvjgwzpnw"/><defs><linearGradient id="SVGyYQWPcRW" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="erg-8lbed"/><stop offset="1" class="rq9_-xb6b"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:masq" {...props}></Icon>
<style>
:global(.erg-8lbed) {
  stop-color: var(--svg-color--00c0ff, #00c0ff);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.qvjgwzpnw) {
  d: path("M17.536 5.199c-2.906-2.932-8.163-2.932-11.07 0c-2.905 2.932-2.905 8.142 0 11.08l2.45 2.046v-1.877c0-1.07.58-2.875 2.226-4.341a253 253 0 0 1 3.364-2.937l.067.133l-2.536 2.438c-.514.67-1.543 2.433-1.543 4.146c0 1.857.7 3.662 1.919 5.113l5.123-5.175a7.57 7.57 0 0 0 0-10.626");
}

:global(.rq9_-xb6b) {
  stop-color: var(--svg-color--0188fe, #0188fe);
}

</style>
