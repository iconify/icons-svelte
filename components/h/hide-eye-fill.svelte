<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue2y6hb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ue2y6hb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:hide-eye-fill" {...props}></Icon>
