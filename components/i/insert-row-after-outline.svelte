<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j685fqbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j685fqbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:insert-row-after-outline" {...props}></Icon>
