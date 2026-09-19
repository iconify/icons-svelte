<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7lxjbmbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7lxjbmbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:italic" {...props}></Icon>
