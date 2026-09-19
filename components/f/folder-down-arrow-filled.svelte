<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr-_ztizn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fr-_ztizn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:folder-down-arrow-filled" {...props}></Icon>
