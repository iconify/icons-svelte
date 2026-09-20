<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9xbkrbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v9xbkrbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mood-smile-outline" {...props}></Icon>
