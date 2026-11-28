<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r63-8hiww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r63-8hiww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dog-solid" {...props}></Icon>
