<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq2-ldpak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nq2-ldpak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:biochemistry-laboratory" {...props}></Icon>
