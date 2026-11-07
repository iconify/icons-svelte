<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahcs-h-rh.css';
import '../../css/f/fzr5emvaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahcs-h-rh"/><path clip-rule="evenodd" class="fzr5emvaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-left-close-outline" {...props}></Icon>
