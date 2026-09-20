<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xra610bcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xra610bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:i18next" {...props}></Icon>
