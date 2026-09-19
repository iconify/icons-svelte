<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d75lzfbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d75lzfbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:number-5" {...props}></Icon>
