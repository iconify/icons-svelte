<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czdsxrb2c.css';
import '../../css/e/ewaos-x_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czdsxrb2c"/><path class="ewaos-x_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clouds-bold-duotone" {...props}></Icon>
