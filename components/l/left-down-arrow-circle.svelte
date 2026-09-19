<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj98ueone.css';
import '../../css/t/t95d9j63b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj98ueone"/><path class="t95d9j63b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:left-down-arrow-circle" {...props}></Icon>
