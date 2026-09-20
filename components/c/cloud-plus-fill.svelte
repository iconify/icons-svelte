<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nae_7cc8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nae_7cc8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-plus-fill" {...props}></Icon>
