<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssso-fkbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ssso-fkbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-2-outline" {...props}></Icon>
