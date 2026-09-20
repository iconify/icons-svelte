<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGxUOMRb3d" x1="99.991%" x2=".01%" y1="-.011%" y2="100.01%"><stop offset=".344%" class="qea20536a"/><stop offset="46.89%" class="u1ts3dbke"/><stop offset="100%" class="z2w67ghwc"/></linearGradient></defs><path fill="url(#SVGxUOMRb3d)" class="kfztbhshm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:kotlin-icon" {...props}></Icon>
<style>
:global(.kfztbhshm) {
  d: path("M256 256H0V0h256L128 127.949z");
}

:global(.qea20536a) {
  stop-color: var(--svg-color--e44857, #e44857);
}

:global(.u1ts3dbke) {
  stop-color: var(--svg-color--c711e1, #c711e1);
}

:global(.z2w67ghwc) {
  stop-color: var(--svg-color--7f52ff, #7f52ff);
}

</style>
