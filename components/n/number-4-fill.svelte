<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfuushbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zfuushbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-4-fill" {...props}></Icon>
