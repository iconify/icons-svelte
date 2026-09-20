<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvm0zswmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvm0zswmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:list-number-solid" {...props}></Icon>
