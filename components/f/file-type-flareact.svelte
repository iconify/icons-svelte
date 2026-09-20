<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGIwk4Sc5y" x1="305.289" x2="307.299" y1="875.967" y2="848.006" gradientTransform="translate(-290 -846)" gradientUnits="userSpaceOnUse"><stop offset="0" class="h2k618njp"/><stop offset="1" class="qntovs8hh"/></linearGradient><linearGradient id="SVGqAn69dfI" x1="305.465" x2="306.435" y1="873.262" y2="859.512" gradientTransform="translate(-290 -846)" gradientUnits="userSpaceOnUse"><stop offset="0" class="xsh36iagy"/><stop offset="1" class="tbipo9bor"/></linearGradient></defs><path fill="url(#SVGIwk4Sc5y)" class="ai-cecbya"/><path fill="url(#SVGqAn69dfI)" class="vs5tfbnud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-flareact" {...props}></Icon>
<style>
:global(.ai-cecbya) {
  d: path("M26.614 20.792c-.41 5.46-5.52 9.56-11.39 9.17s-10.27-5.13-9.84-10.58c.57-7.52 12-17.37 12-17.37c-3.66 10 10 8.82 9.23 18.78");
}

:global(.h2k618njp) {
  stop-color: var(--svg-color--ffebc8, #ffebc8);
}

:global(.qntovs8hh) {
  stop-color: var(--svg-color--ffa95f, #ffa95f);
}

:global(.tbipo9bor) {
  stop-color: var(--svg-color--ee6f05, #ee6f05);
}

:global(.vs5tfbnud) {
  d: path("M10.554 22.742a5 5 0 0 0 4.8 5.189h.026a5.1 5.1 0 0 0 5.58-4.49c.29-3.7-4.52-9.2-4.52-9.2c1.034 5.101-5.506 3.631-5.886 8.501");
}

:global(.xsh36iagy) {
  stop-color: var(--svg-color--fab743, #fab743);
}

</style>
