<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk3gbqpff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mk3gbqpff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:polygon-24px" {...props}></Icon>
