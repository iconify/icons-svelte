<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flxmbubhy.css';
import '../../css/n/nvklklbjn.css';
import '../../css/r/ri6h5bc1k.css';
import '../../css/r/rbjjgofgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flxmbubhy"/><path class="nvklklbjn"/><path class="ri6h5bc1k"/><path clip-rule="evenodd" class="rbjjgofgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:banknote-bold-duotone" {...props}></Icon>
