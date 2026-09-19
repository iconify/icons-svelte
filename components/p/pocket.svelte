<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd7m8bbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd7m8bbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:pocket" {...props}></Icon>
