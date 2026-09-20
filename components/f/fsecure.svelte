<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfd79i_uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfd79i_uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fsecure" {...props}></Icon>
