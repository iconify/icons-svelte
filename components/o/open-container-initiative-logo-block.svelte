<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywec42b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ywec42b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:open-container-initiative-logo-block" {...props}></Icon>
