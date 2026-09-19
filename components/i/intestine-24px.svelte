<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m16zfhb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m16zfhb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:intestine-24px" {...props}></Icon>
