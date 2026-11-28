<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdvmxhb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdvmxhb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:car-taxi-solid" {...props}></Icon>
