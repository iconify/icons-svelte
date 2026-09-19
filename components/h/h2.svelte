<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdur_ohrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdur_ohrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:h2" {...props}></Icon>
