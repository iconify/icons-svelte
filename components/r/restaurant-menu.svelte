<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlg_-wbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wlg_-wbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:restaurant-menu" {...props}></Icon>
