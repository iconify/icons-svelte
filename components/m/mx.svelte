<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mukfgmbez.css';
import '../../css/y/ynttdhfug.css';
import '../../css/p/p9bu9v51v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mukfgmbez"/><path class="ynttdhfug"/><path class="p9bu9v51v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mx" {...props}></Icon>
