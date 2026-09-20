<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niy8yfjwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="niy8yfjwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:image-edit-fill" {...props}></Icon>
