<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h555ks16l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h555ks16l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:regex-solid" {...props}></Icon>
