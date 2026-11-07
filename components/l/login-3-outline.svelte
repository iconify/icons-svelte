<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c55umkfci.css';
import '../../css/n/nfvqnvzcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c55umkfci"/><path clip-rule="evenodd" class="nfvqnvzcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:login-3-outline" {...props}></Icon>
