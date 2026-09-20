<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kevvj2bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kevvj2bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-i-square-solid" {...props}></Icon>
