<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkq-4jiie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkq-4jiie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:drafting-compass" {...props}></Icon>
