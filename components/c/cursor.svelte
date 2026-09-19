<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibpc1qyqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibpc1qyqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:cursor" {...props}></Icon>
