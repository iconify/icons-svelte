<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb_u2dh5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nb_u2dh5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:folder-medical-filled" {...props}></Icon>
