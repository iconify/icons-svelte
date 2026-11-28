<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1atj4rea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1atj4rea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-number-3-solid" {...props}></Icon>
