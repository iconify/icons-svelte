<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya2mhfiow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya2mhfiow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:align-left-filled" {...props}></Icon>
