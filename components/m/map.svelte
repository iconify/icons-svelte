<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md8a7y_mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md8a7y_mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:map" {...props}></Icon>
