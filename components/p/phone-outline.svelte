<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy1nb0bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy1nb0bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:phone-outline" {...props}></Icon>
