<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmrki3njp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gmrki3njp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:restart-outline" {...props}></Icon>
