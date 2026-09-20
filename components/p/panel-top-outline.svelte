<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjndzv7wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gjndzv7wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-top-outline" {...props}></Icon>
