<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4sr2psho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4sr2psho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-cog-solid" {...props}></Icon>
