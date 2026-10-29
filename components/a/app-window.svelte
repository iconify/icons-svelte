<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbk7k8bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbk7k8bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:app-window" {...props}></Icon>
