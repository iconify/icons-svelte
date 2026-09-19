<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v33sube9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v33sube9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:modified-date" {...props}></Icon>
