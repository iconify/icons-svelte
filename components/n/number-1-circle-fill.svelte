<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hznh8nbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hznh8nbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-1-circle-fill" {...props}></Icon>
