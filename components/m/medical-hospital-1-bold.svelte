<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7hybswkg.css';
import '../../css/o/o08b9ebzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7hybswkg"/><path class="o08b9ebzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:medical-hospital-1-bold" {...props}></Icon>
