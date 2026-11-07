<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3vf0gi4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3vf0gi4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:eye-closed-linear" {...props}></Icon>
