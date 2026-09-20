<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlnpkubhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlnpkubhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:eye-fill" {...props}></Icon>
