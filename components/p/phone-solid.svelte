<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je0lvqbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="je0lvqbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:phone-solid" {...props}></Icon>
