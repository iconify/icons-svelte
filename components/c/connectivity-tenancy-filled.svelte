<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azy9twppz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azy9twppz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:connectivity-tenancy-filled" {...props}></Icon>
