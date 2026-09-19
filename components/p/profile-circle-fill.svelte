<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg3ev6byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gg3ev6byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:profile-circle-fill" {...props}></Icon>
