<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y--pbs6ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y--pbs6ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:plus-square-fill" {...props}></Icon>
