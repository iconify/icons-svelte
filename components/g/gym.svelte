<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugxksv4ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugxksv4ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:gym" {...props}></Icon>
