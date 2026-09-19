<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfpuc6bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nfpuc6bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pain-managment" {...props}></Icon>
