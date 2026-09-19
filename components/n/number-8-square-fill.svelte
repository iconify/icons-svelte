<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnox6ln0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mnox6ln0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-8-square-fill" {...props}></Icon>
