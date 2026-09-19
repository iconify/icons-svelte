<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz609_phz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz609_phz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:number-2" {...props}></Icon>
