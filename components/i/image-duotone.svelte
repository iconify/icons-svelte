<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnvj0fsqr.css';
import '../../css/k/kqkvu1bgm.css';
import '../../css/a/a22-aez3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnvj0fsqr"/><path class="kqkvu1bgm"/><path class="a22-aez3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-duotone" {...props}></Icon>
