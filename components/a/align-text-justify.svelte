<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io1nb8brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io1nb8brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:align-text-justify" {...props}></Icon>
