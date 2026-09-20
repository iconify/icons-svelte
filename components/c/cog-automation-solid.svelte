<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf-n46rwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nf-n46rwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:cog-automation-solid" {...props}></Icon>
