<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipmluib_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipmluib_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-circle-left" {...props}></Icon>
