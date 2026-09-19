<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/papf5x-vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="papf5x-vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:birthday-cake" {...props}></Icon>
