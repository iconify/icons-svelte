<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfz19cbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfz19cbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bluetooth" {...props}></Icon>
