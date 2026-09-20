<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6akpzbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m6akpzbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-security-outline" {...props}></Icon>
