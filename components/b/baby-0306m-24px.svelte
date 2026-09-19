<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvhey3wrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvhey3wrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:baby-0306m-24px" {...props}></Icon>
