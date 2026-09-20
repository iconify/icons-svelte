<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxulecbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxulecbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:film-open-edit" {...props}></Icon>
