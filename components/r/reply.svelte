<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqw20ubea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqw20ubea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:reply" {...props}></Icon>
