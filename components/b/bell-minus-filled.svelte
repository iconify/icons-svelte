<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb3kqobhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb3kqobhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bell-minus-filled" {...props}></Icon>
