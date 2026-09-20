<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teucm-ivn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="teucm-ivn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:menu-down-outline" {...props}></Icon>
